1. check status
get system ha status
  Master: FGXXXXX1, operating cluster index = 0
  Slave : FGXXXXX2, operating cluster index = 1
2. conecct to slave
execute ha manage 1

#### If you will see error:
  WARNING: File System Check Recommended! Unsafe reboot may have caused inconsistency in disk drive.
  It is strongly recommended that you check file system consistency before proceeding.
  Please run 'execute disk scan 17'
  Note: The device will reboot and scan during startup. This may take up to an hour
