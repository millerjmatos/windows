Verifica a integridade e restaura problemas relacionados a disco:

    chkdsk /r

Verifica a integridade e restaurar arquivos de sistema:

    sfc /scannow

Deployment Image Servicing and Management:

    dism /online /cleanup-image /restorehealth

Corrigindo o erro de Credssp: 

    REG ADD  HKLM\Software\Microsoft\Windows\CurrentVersion\Policies\System\CredSSP\Parameters\ /v AllowEncryptionOracle /t REG_DWORD /d 2