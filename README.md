# Symfony Helper


### Delete cache
	 sudo rm -rf var/cache/*

### cache bust 
	composer dumpautload

### Symfony Profiler /  very helpful to debug
	
```
directory : /web/app.php

use Symfony\Component\Debug\Debug;

Debug::enable(E_ERROR);

$kernel = new AppKernel($environment, true);
```
