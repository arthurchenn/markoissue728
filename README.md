Prerequisite:
  1, git clone https://github.com/arthurchenn/markoissue728
  2, cd markoissue728
  3, npm install


How to reproduce the problem:

  1) remove the comment tags enclosing <await> tag from file src/pages/home/public.marko
  2) webpack
  3) cd target/markoissue728
  4) node ./server.js

  you should see the error.


How to fix the problem:
  1) comment out <await> tag from file src/pages/home/public.marko
  2) webpack
  3) cd target/markoissue728
  4) node ./server.js

  you can now browse to http://localhost:3000, see the hello world page.
