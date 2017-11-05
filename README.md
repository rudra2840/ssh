Painel SSH


VPS Manager

O VPS Manager é conjunto de scripts feitos pra configurar automaticamente Proxy Squid e OpenSSH em servidores Linux, além de instalar comandos para facilitar o gerenciamento de usuários. Documentação: VPS Manager 2.0 - Documentação.pdf

Versão 1.0 

wget http://pastebin.com/raw/hMU40FtW && bash hMU40FtW && bash install
vpspack

Versão 2.0 

wget https://raw.githubusercontent.com/marceloccms/ssh/master/vpsmanager/vpsmanagersetup.sh openvpn-install.sh && bash openvpn-install.sh

chmod +x vpsmanagersetup.sh
./vpsmanagersetup.sh

TCP Tweaker

O TCP Tweaker um script experimental que altera algumas configurações de rede do sistema Linux para melhorar a velocidade e estabilidade da conexão Proxy, VPN ou Túnel SSH. Caso as alterações não melhorem a navegação e estabilidade, basta executar o script novamente para desfazê-las.

wget http://phreaker56.obex.pw/tcptweaker.sh
chmod +x tcptweaker.sh
./tcptweaker.sh

OpenVPNSetup

O OpenVPNSetup é uma versão modificada do script openvpn-install para funcionar com o protocolo TCP com interface em português. Ele serve para facilitar a configuração de servidor OpenVPN e a criação de certificados de usuários (arquivos .ovpn) em servidores VPS ou Cloud Linux que rodem Debian, Ubuntu ou CentOS sem o utilizador precisar de conhecimento técnico.

wget https://git.io/vpn -O openvpn-install.sh && bash openvpn-install.sh





