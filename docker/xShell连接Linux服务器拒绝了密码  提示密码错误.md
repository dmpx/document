xShell����Linux��������ʾ������� 
1����������SSH�����Ƿ����� 
service sshd status�����û�п�������ִ��service sshd start�����÷��񣬻���ͨ��service sshd restart�����÷���

2����� /etc/ssh/ssh_config�ļ��� 
ssh����˿��Ƿ�Ϊ22��ProtocolЭ��汾�Ƿ�Ϊ2��һ��Ϊ2��ȫ��1Ϊssh 1����ȫ���п��ܽ�ֹ��½���� 
3�����/etc/ssh/sshd_config�� 
��

    # Authentication:
    LoginGraceTime 120
    PermitRootLogin without passwd
    StrictModes yes

�ĳ�
    # Authentication:
    LoginGraceTime 120
    PermitRootLogin yes
    StrictModes yes

����
��SSH���ñ�ע�͵�ʱ����ע���ͷžͿ��ԡ�
�����������