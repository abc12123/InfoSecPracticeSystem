����ʡ��Ϣ��ȫ����
------------------

������ʽ��
  * ����Ԥѡ���������������ڹ涨ʱ���ڵ�¼ָ������վ�������ߴ��ⷽʽ���У��������ͷ�Ϊ�ж��⡢��ѡ��Ͷ�ѡ�⡣
  * �ֳ���������������Կ�������ͨ�ؾ�����ʽ���У���ȡ�����������Կ���ͻ�����ݵ�ʵս������Ŀ�������漰��ע�롢�������������̽����վ���ƽ⡢�ӽ��ܡ���Ϣ���صȳ��ü�����Կ������ֶΡ�
 
��ϵͳ��������������Ԥѡ���������Լ��ٷ��������⣬�����ߴ��ⷽʽ���У��������ͷ�Ϊ�ж��⡢��ѡ��Ͷ�ѡ�⡣����������Ŵ�˳�򣬽���Ϊ����ѡ�ֵĺ�ϵͳ��
 
��ϵͳ��Ϊ˳����ϰ�������ϰ��ģ����������⼯�ȶ��ģ�顣�뾡�������ϵͳ������Ŀ��ְ�~

����
----

### ��������
  * Microsoft Visual Studio 2010
  * SQL Server 2008  
  * Adobe Dreamweaver

### �ͻ���
  * ���������
  
### ��������
  * SQL Server 2008
  * .NET 4.0
  * IIS 6.0
  * Windows Server 2008

��������
--------

### ���ݿ�����
  * 1���������ݿ⵽SQL Server 2008�У���Ŀ¼Ϊ`.\Code\App_Data\InformationSecurity.mdf`��
  * 2������`InformationSecurity`���ݿ���û��������롣
  * 3���޸�`.\Code\web.config`��`connectionStrings`���ԣ����£�

```C#
  <connectionStrings>
		<add name="ConnectionString" connectionString="Data Source=.;Initial Catalog=InformationSecurity;Persist Security Info=True;User ID=~~���ݿ��û���~~;Password=~~���ݿ�����~~" providerName="System.Data.SqlClient" />
	</connectionStrings>
```

### ������վ
  * 1��������� -> ����͹��� -> �򿪻�ر�windows���ܣ���ߣ� -> Internet��Ϣ����ѡ�����£�
    ![��װIIS](https://github.com/liuker0x007/InfoSecPracticeSystem/blob/master/README/01.png)
  * 2������ϵͳĬ��ƽ̨��Ĭ����`.NET2.0`��Ҫ����Ϊ`.NET4.0`����
    ![����ϵͳĬ��ƽ̨](https://github.com/liuker0x007/InfoSecPracticeSystem/blob/master/README/02.png)
  * 3��������� -> ������ -> Internet��Ϣ����IIS�������� -> �����վ��JX3Report����Ĭ�϶˿ں���Ϊ80��
    ![������վ](https://github.com/liuker0x007/InfoSecPracticeSystem/blob/master/README/03.png)
  * 4��Ӧ�ó���� -> ���Ӧ�ó���ء�
    ![�޸�Ӧ�ó����](https://github.com/liuker0x007/InfoSecPracticeSystem/blob/master/README/04.png)
    ![�޸�Ӧ�ó����](https://github.com/liuker0x007/InfoSecPracticeSystem/blob/master/README/05.png)
  * 5�������Ĭ���ĵ�����������վ��Ĭ���ĵ���
    ![������վ��Ĭ���ĵ�](https://github.com/liuker0x007/InfoSecPracticeSystem/blob/master/README/06.png)
    ![������վ��Ĭ���ĵ�](https://github.com/liuker0x007/InfoSecPracticeSystem/blob/master/README/07.png)

### ��������
  * ��`.\Code\App_Code\Comman\settings.cs`�иĳ�����������

```C#
  string domain = "http://����:�˿ں�";   //eg.http://www.liuker.xyz������˿ں���80����Բ��üӶ˿ںš�
```

��ϵ��ʽ
--------

  * E-mail��lzq@liuker.xyz
  * QQ��2523417411
