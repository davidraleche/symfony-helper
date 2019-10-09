# PHP Favorite Twist
	

## Ternary
```
$data['username'] = (isset($data['username']) ? $data['username'] : 'guest');
```

## PHP 7
```
$username = $_SESSION['username'] ?? 'guest';
```

## PHP 7.4 New
```
$data['username'] ??= 'guest'
```

## Elvis Operator
```
foo = bar ?: baz;

roughly resolves to

foo = bar ? bar : baz;
```