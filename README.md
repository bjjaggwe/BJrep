# BJrep
conn_path <- paste("DRIVER=",dsn_driver,
  ";DATABASE=",dsn_database,
                  ";HOSTNAME=",dsn_hostname,
                  ";PORT=",dsn_port,
                  ";PROTOCOL=",dsn_protocol,
                  ";UID=",dsn_uid,
                  ";PWD=",dsn_pwd,
                  ";SECURITY=",dsn_security,        
                    sep="")
conn <- odbcDriverConnect(conn_path)
conn

Warning message in odbcDriverConnect(conn_path):
“[RODBC] ERROR: state 01000, code 0, message [unixODBC][Driver Manager]Can't open lib 'com.ibm.db2.jcc.DB2Driver' : file not found”Warning message in odbcDriverConnect(conn_path):
“ODBC connection failed”
