�ʺϾ��󲿷�VPSʹ�� 

DD�ɹ���oci  aws  az  rn  vultr  layerstack

��װ

bash <(wget --no-check-certificate -qO- 'https://raw.githubusercontent.com/MoeClub/Note/master/InstallNET.sh') -d 11 -v 64 -p 123456 -port 22


ϵͳ����

-d 10  ��7��8��9��10��11��Debian

-u 20.04  ��14.04��16.04��18.04��20.04��Ubuntu

������������Ըĳɱ��


-p 12345

�˿ڲ���

port 22


��װ��ɺ�VPS��������װ���ȴ�10�������ң�������������

�û���Ϊroot

�����������õ�

�ɹ����Ӻ���������ĸ��������BBR������ƻ���ϵͳ����


�������

apt update -y && apt install -y curl && apt install -y socat && apt install wget -y

BBR

wget -N --no-check-certificate "https://raw.githubusercontent.com/chiakge/Linux-NetSpeed/master/tcp.sh" && chmod +x tcp.sh && ./tcp.sh