# AH PROJECT

Naive World of Warcraft addon using Auction House API. 

## Getting Started with LUA

Lua is a scripting language used to make addons. If you haven't used LUA before, it is not difficult to get started.

### Here are some good sources to get started:

- Official Docs: http://www.lua.org/home.html
- Compiler via browser: https://www.lua.org/cgi-bin/demo?hello
- WoW addon guide: https://www.wowhead.com/guide=1949/wow-addon-writing-guide-part-one-how-to-make-your-first-addon

### Installing LUA for MacOS:

1. Open up terminal and type.
```
curl -R -O http://www.lua.org/ftp/lua-5.3.5.tar.gz
tar zxf lua-5.3.5.tar.gz
cd lua-5.3.5
make macosx test
```

2. Once installed, you need to copy the lua into /usr/loca/bin/.
```
sudo cp src/lua /usr/local/bin
```

3. Test it via command line.
```
lua
> io.write("Hello world, from ", _VERSION, "!\n")
```

output
```
Hello world, from Lua 5.3!
file (0x7fff990ab1a8)
```

4. Test a program.

Create a file named helloworld.lua. Copy and save the program below:

```
-- helloworld.lua
-- the first program in every language

io.write("Hello world, from ",_VERSION,"!\n")
```

To run it, enter this command in terminal.
```
lua helloworld.lua
```

## Built With

* [LUA](https://www.lua.org) - The compiler used

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Abe Choi** - *Initial work*

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* README Template by https://github.com/PurpleBooth

