# laravel-editormd
<h1 align="center"> laravel-editormd </h1>

<p align="center"> .</p>


## Installing

```shell
$ composer require cnpscy/laravel-editormd -vvv
```

- 在`config/app`的`provider`新增
```
Cnpscy\Editormd\EditorMdProvider::class,
```

- 生成配置文件
```
php artisan vendor:publish
```

## Usage

TODO

## Contributing

You can contribute in one of three ways:

1. File bug reports using the [issue tracker](https://github.com/cnpscy/laravel-editormd/issues).
2. Answer questions or fix bugs on the [issue tracker](https://github.com/cnpscy/laravel-editormd/issues).
3. Contribute new features or update the wiki.

_The code contribution process is not very formal. You just need to make sure that you follow the PSR-0, PSR-1, and PSR-2 coding guidelines. Any new code contributions must be accompanied by unit tests where applicable._

## 感谢
- Laravel
- 基于扩展包`laravelchen/laravel-editormd`做了简单的改动

## License

MIT