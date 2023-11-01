# Creating a Self-Signed Certificate using server configuration file
openssl req  -nodes -new -x509 -config server.cnf -extensions req_ext -keyout server.key -out server.crt
