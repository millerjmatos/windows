### TRANSFORMANDO O WINDOWS SERVER STANDARD EVALUATION EM ORIGINAL:

Verificar a versão atual do Windows Server: 
    
    dism /online /get-currentedition

Verificar para qual versão poderá ser atualizado o Windows: 
    
    dism /online /get-targeteditions

Fazer a conversão baseado na versão desejada e entre as possíveis: 
    
    dism /online /set-edition: NOMEVERSÃODESEJADA /productkey: XXXXX-XXXXX-XXXXX-XXXXX-XXXXX /accepteula