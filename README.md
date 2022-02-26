import socket as s

#host do site que voçe que ver o ip#
host = 'google.com'

#captura o ip do host captado#

ip = s.gethostbyname(host)
print(' O IP DO HOST "' + host + '" é: ' + ip)
