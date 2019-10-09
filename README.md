# Symfony Helper

### Symfony Profiler /  very helpful to debug
	
```
directory : /web/app.php

use Symfony\Component\Debug\Debug;

Debug::enable(E_ERROR);

$kernel = new AppKernel($environment, true);
```
