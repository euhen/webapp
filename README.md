Test project on N2O Web Framework
=================================

This test project is based on examples that provided with the N2O framework.

Здесь добавлены несколько строчек кода и какой-то html-шаблон, вероятно, откуда-то скопированный.
Затем была протестирована работа с БД посредством Erlang-ноды на Java, но до написания модуля Erlang для работы с БД не дошло.

Prerequisites
-------------

* erlang
* mad
* inotify-tools (Linux, for filesystem watching)
* uglify (assets)

Run
---

To run just perform on Windows, Linux and Mac

    $ ./mad deps compile plan repl

On BSD you should use gmake

And open it in browser [http://localhost:8000](http://localhost:8000)
If you want to try pure Single Page Application (SPA) wich
connects to Erlang N2O Application Server you should use
[http://localhost:8000/static/spa/spa.htm](http://localhost:8000/static/spa/spa.htm)

For full features of make please refer to [https://github.com/synrc/otp.mk](https://github.com/synrc/otp.mk)

Credits
-------

* Maxim Sokhatsky

OM A HUM
