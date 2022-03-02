# Laravel 9 pt_BR Language Files

Este repositório contém os arquivos de mensagens no idioma Português Brasileiro (pt_BR) para o <a href="https://laravel.com/" target="_blank">Laravel 9</a>, incluindo Laravel Jetstream com Livewire

## Instruções para instalação:

1) Clone o repositório para sua máquina
```bash
git clone https://github.com/cpereiraweb/laravel9-pt-br-language-files.git
```

2) Copie o arquivo `pt_BR.json` e a pasta `pt_BR` para a pasta `lang` do seu projeto Laravel 9.

3) Edite o arquivo `config/app.php` para alterar o idioma (linhas 85 e 111):
```php
...
    /*
    |--------------------------------------------------------------------------
    | Application Locale Configuration
    |--------------------------------------------------------------------------
    |
    | The application locale determines the default locale that will be used
    | by the translation service provider. You are free to set this value
    | to any of the locales which will be supported by the application.
    |
    */

    'locale' => 'pt_BR',
...
   /*
    |--------------------------------------------------------------------------
    | Faker Locale
    |--------------------------------------------------------------------------
    |
    | This locale will be used by the Faker PHP library when generating fake
    | data for your database seeds. For example, this will be used to get
    | localized telephone numbers, street address information and more.
    |
    */

    'faker_locale' => 'pt_BR',
...
```

E é isso!

Para mais detalhes sobre customizações de tradução no Laravel, veja a <a href="https://laravel.com/docs/9.x/localization" target="_blank">página da documentação aqui</a>.


Happy coding!