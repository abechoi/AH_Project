AH PROJECT README
By Abe Choi
Simple and naive auction house addon.


Getting Started with LUA:

If you haven't used LUA before, it is not difficult to get started as it is not a difficult language to understand.

Here are some good sources to get started with lua:
- Official Docs: http://www.lua.org/home.html
- Compiler via browser: https://www.lua.org/cgi-bin/demo?hello


Installing LUA for MacOS:

1. Open up terminal and type.
curl -R -O http://www.lua.org/ftp/lua-5.3.5.tar.gz
tar zxf lua-5.3.5.tar.gz
cd lua-5.3.5
make macosx test

2. Once installed, you need to copy the lua into /usr/loca/bin/.
sudo cp src/lua /usr/local/bin

3. Test it via command line.
lua
> io.write("Hello world, from ", _VERSION, "!\n")

4. Test a program.
- Create a file named helloworld.lua. Copy and save the program below:
-- hello.lua
-- the first program in every language

io.write("Hello world, from ",_VERSION,"!\n")

- Run it in terminl by typing...
lua helloworld.lua


