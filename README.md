segfaultCat
===========

Basic reverse-proxy webserver


Structure and labour assignments:

Vlad:
config_parser.cc/ch contains the functions needing for
                    parsing the config file
James:
webserver.cc/ch     contains classes/functions used for
                    request check and sending stuff
                    calls parse_config(char * file_path,
                                       int listening port)
                    (declaration is char* , int&)
build.sh
unit tests to be determined
