# NODEPP-MySQL
Run **MySQL** in Nodepp

## Dependencies
- libmysqlclient-dev
  - 🪟: `pacman -S mingw-w64-x86_64-libmariadbclient`
  - 🐧: `sudo apt install libmysqlclient-dev`

## Compilation
`g++ -o main main.cpp -I ./include -lmysqlclient ; ./main`
