���汾Ŀ¼����ʹ��˵����

RestServerֱ�ӷ������ݿ�Ϊjson��ʽ�ṩ����

RestSerRestServerֱ�ӷ������ݿ�Ϊjson��ʽ ֧��MySQL,SqlServer,Oracleֱ�ӷ���ΪRest���� ����json��ʽ���ͻ���

�����ļ����ѹ

 

RestServer��һ����ݵ�rest������������ֱ�ӽ����ݿ����ݷ�����json��ʽ����������Ҫjson��ʽ���ݵĵط����á��˳�����ѣ������г��ṩ��1.0.0.22֧�����б����ݷ����Լ��������������ء�

ʹ�û�����

1)     ������:windows xp,7,8,10,windows server 2003,2008,2012��.

2)     .netFrameWork 4.0��

3)     ���ݿ�:oracle 9i,10g,11g,MSSql2000,2005,2008,2012,MySQL5���ϡ�

 

1)     ��ѹ�������ӦĿ¼����ѹ����Ҫ�������ļ���

 

2)     ��װ.net Framework4.0(ȥ΢��ٷ���վ���ػ��������������ɡ�)

3)     ���������ļ��������ļ���Ŀ¼��RestServer.exe.configʹ�ü��±��򿪼��ɽ��б༭�޸ġ�ֻ���޸�configuration/appSettings���ý���������ݣ�����֮ǰ����Ƚ��и��Ʊ��ݣ�Ȼ���ٽ����޸ģ��������ļ�˵�����£�

<add key="HOSTNAME"value="localhost"/><!--����������-->

    <addkey="PORT" value="9001"/><!--Restf����˿�-->

    <add key="DBTYPE"value="MYSQL"/><!--ORACLE,MSSQL,MYSQL-->

    <addkey="DBCONSTRING" value="UserId=root;Host=localhost;Database=db_carmanager;password=root"/>

    <!--[SQL]: Data Source= 192.168.0.21; Initial Catalog = testtable; User Id = sa; Password = 123456;-->

    <!--[ORACLE]: DataSource = Data Source=carorcl;Persist Security Info=True;UserID=zcb;Password=zcb-->

    <!--[MySQL]: UserId=root;Host=localhost;Database=db_carmanager;password=root-->

<add key="TABLES"value="t_log,t_car"/> <!--t_test ,�ָ�-->

a)        HOSTNAMEΪ��ǰ��������,id��ַ������

b)        PORTΪ��Ҫʹ�õĶ˿ڣ���ʹ��ϵͳû���õķ���ᴴ��ʧ�ܡ�

c)        DBTYPEΪ���ݿ����� ����ΪORACLE,MSSQL��MYSQL���ֱ��Ӧʹ��ORACLE���ݿ�,MSSqlServer,MySQL���ݿ⡣

d)        DBCONSTRINGΪ���ݿ���������� ��ο��·���������DBTYPE���ͽ������á�

4)     �������ע��win7����ϵͳ����Server 2008����ϵͳ��ʹ���Ҽ�����Ա��ʽִ�У����������ʧ�ܡ������ɹ������������ʾ��

 

��ʾ�����Ѿ������ɹ������������ǾͿ��������ˡ�

 

1.  ��ʼʹ��

�����ɹ���Ϳ���ʹ���ˡ�������һ��������t_log��t_car���ű�

��ʱ�����ǾͿ�����IE��������������ݽ��в�����

1)     ��ѯ�����������ݷ���json,����http://localhost:9001/rest/t_car/query���ǾͿ�����������п������½����

 

2)     ������Ҫ�Ա���в�ѯ������carno="ɽA23392"��ʱ�����ǿ��Խ������²�ѯ��http://localhost:9001/rest/t_car/query/carno=carno="ɽA23392"��ʱ���������ʾ���£�

 

��Ȼ����߿���֧��sql����е�where��������ϲ�ѯ������Ͳ�������ϸ˵���ˡ�

 


BUG����
 QQ:80163278
 ����:devgis@qq.com
 �Ա�:http://flysoft.taobao.com
 ----------------------------------------------------------------------------------------------
 1.1
 jsonp��ʽ֧�ַ���JQUERY����
 ��־��¼����
 �������ķ�ʽд���ݽ����Ż��Ż�
 ----------------------------------------------------------------------------------------------
 1.0
 ��������
 ----------------------------------------------------------------------------------------------

 

�ٶ��������ص�ַ��http://pan.baidu.com/s/1bn2szDH 
 CSDN���ص�ַ��http://download.csdn.net/user/devgis

C#,WinForm ,���ݿ⣬MapXtreme, Arcgis Engine ��صĿ���,����211��У��ҵ�������Ѿ�����8����ؿ����������������������������ϵ��QQ ��80163278����:devgis@qq.com�۸���Թ�����������ӭ���ں���������