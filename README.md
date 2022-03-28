### PHP ThinkPHP

> ThinkPHP 6.0 (https://www.thinkphp.cn/) require PHP7.2+ (https://www.php.net/), and installed and managed by composer (https://getcomposer.org/), PHP/MySQL/Apache/Nginx were install and managed by BaoTa (https://www.bt.cn/new/index.html)。

### 1. Composer help
``` shell
# composer
composer
---
Composer version 2.2.9 2022-03-15 22:13:37

Usage:
  command [options] [arguments]

Options:
  -h, --help                     Display this help message
  -q, --quiet                    Do not output any message
  -V, --version                  Display this application version
      --ansi                     Force ANSI output
      --no-ansi                  Disable ANSI output
  -n, --no-interaction           Do not ask any interactive question
      --profile                  Display timing and memory usage information
      --no-plugins               Whether to disable plugins.
      --no-scripts               Skips the execution of all scripts defined in composer.json file.
  -d, --working-dir=WORKING-DIR  If specified, use the given directory as working directory.
      --no-cache                 Prevent use of the cache
  -v|vv|vvv, --verbose           Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug

Available commands:
  about                Shows a short information about Composer.
  archive              Creates an archive of this composer package.
  browse               Opens the packages repository URL or homepage in your browser.
  cc                   Clears composers internal package cache.
  check-platform-reqs  Check that platform requirements are satisfied.
  clear-cache          Clears composers internal package cache.
  clearcache           Clears composers internal package cache.
  config               Sets config options.
  create-project       Creates new project from a package into given directory.
  depends              Shows which packages cause the given package to be installed.
  diagnose             Diagnoses the system to identify common errors.
  dump-autoload        Dumps the autoloader.
  dumpautoload         Dumps the autoloader.
  exec                 Executes a vendored binary/script.
  fund                 Discover how to help fund the maintenance of your dependencies.
  global               Allows running commands in the global composer dir ($COMPOSER_HOME).
  help                 Displays help for a command
  home                 Opens the packages repository URL or homepage in your browser.
  i                    Installs the project dependencies from the composer.lock file if present, or falls back on the composer.json.
  info                 Shows information about packages.
  init                 Creates a basic composer.json file in current directory.
  install              Installs the project dependencies from the composer.lock file if present, or falls back on the composer.json.
  licenses             Shows information about licenses of dependencies.
  list                 Lists commands
  outdated             Shows a list of installed packages that have updates available, including their latest version.
  prohibits            Shows which packages prevent the given package from being installed.
  reinstall            Uninstalls and reinstalls the given package names
  remove               Removes a package from the require or require-dev.
  require              Adds required packages to your composer.json and installs them.
  run                  Runs the scripts defined in composer.json.
  run-script           Runs the scripts defined in composer.json.
  search               Searches for packages.
  self-update          Updates composer.phar to the latest version.
  selfupdate           Updates composer.phar to the latest version.
  show                 Shows information about packages.
  status               Shows a list of locally modified packages.
  suggests             Shows package suggestions.
  u                    Upgrades your dependencies to the latest version according to composer.json, and updates the composer.lock file.
  update               Upgrades your dependencies to the latest version according to composer.json, and updates the composer.lock file.
  upgrade              Upgrades your dependencies to the latest version according to composer.json, and updates the composer.lock file.
  validate             Validates a composer.json and composer.lock.
  why                  Shows which packages cause the given package to be installed.
  why-not              Shows which packages prevent the given package from being installed.
---

# composer registry
composer config repo.packagist composer https://mirrors.aliyun.com/composer/

# composer update
composer self-update

# composer install with composer.json
composer install
```
### 2. ThinkPHP install/update
```
# Install ThinkPHP
composer create-project topthink/think tp 6.0.*

# Update ThinkPHP
composer update topthink/framework
```

### 3. Thinkphp run
``` shell
# Run the projcet in the project directory
php think run

# Think help
php think
---
version 6.0.12LTS

Usage:
  command [options] [arguments]

Options:
  -h, --help            Display this help message
  -V, --version         Display this console version
  -q, --quiet           Do not output any message
      --ansi            Force ANSI output
      --no-ansi         Disable ANSI output
  -n, --no-interaction  Do not ask any interactive question
  -v|vv|vvv, --verbose  Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug

Available commands:
  clear             Clear runtime file
  help              Displays help for a command
  list              Lists commands
  run               PHP Built-in Server for ThinkPHP
  version           show thinkphp framework version
 make
  make:command      Create a new command class
  make:controller   Create a new resource controller class
  make:event        Create a new event class
  make:listener     Create a new listener class
  make:middleware   Create a new middleware class
  make:model        Create a new model class
  make:service      Create a new Service class
  make:subscribe    Create a new subscribe class
  make:validate     Create a validate class
 optimize
  optimize:route    Build app route cache.
  optimize:schema   Build database schema cache.
 route
  route:list        show route list.
 service
  service:discover  Discover Services for ThinkPHP
 vendor
  vendor:publish    Publish any publishable assets from vendor packages
---
```