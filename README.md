# cybersecurity

import os 
import pyaes


#Abrir o arquivo criptografado
file_name = 'teste.txt.troll'
file_data = open (file_name, 'rb')
file_data = file.read()
file.close()



#discriptografar 


key = b 'trol'
aes=pyaes.AESmodeofoperationctl(key)
(descrypt)data=aes.descrypt (file_data)


# remover o arquivo discriptografado
os.remove (file_name)

##criar arquvivo de desarme 
new_file = 'teste.txt'
new_file = open{f'{new_file}}', 'wb'
new_file .write (descrypt_data)
new_file.close ()
