# erlang-helloworld
says helloworld erlang style

(instructions for Lubuntu Linux)<br>
install erlang with `sudo apt-get install erlang-base`<br>
make sure you have the compiler with `whereis erlc`<br>
compile with `erlc hello.erl` (compile is probably unnecessary since beam file is included in the repo)<br>
run with command `erl -noshell -s helloworld start -s init stop`<br>

`-noshell` prevents the `erl` command from opening interactive shell, which is what the command does by itself does.<br>
`-s` stands for "script" I'm guessing.<br>
`helloworld` is the module and `start` is a function of the module. I'm guessing the same could be said for `init` and `stop` which terminates the program after it runs


