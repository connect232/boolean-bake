# Boolean Bake plugin for CakePHP

## Installation
Run:
```
composer require connect232/boolean-bake
```
## Usage
Run :
```
bin/cake plugin load BooleanBake
```
Or in your `src/Application.php` add:
```
$this->addPlugin('BooleanBake');
```
in src/Application::bootstrapCli() before loading the 'Bake' plugin. Add
```
Configure::write('Bake.theme', 'BooleanBake');
```
