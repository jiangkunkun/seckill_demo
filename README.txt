Java�߲�����ɱAPI��Ŀ��

1.������Ŀ��mavenָ��

2.�޸�Servlet�汾Ϊ3.1
  ��ȫ��Ŀ�ṹ

3.�޸�junit�汾Ϊ4.11��ʹ��ע�ⷽʽ���ԣ�
  pom.xml��ȫ��Ŀ������
	��־��java��־
	ʵ��slf4j�ӿڲ�����
	���ݿ��������
	DAO��ܣ�MyBatis����
	MyBatis����ʵ�ֵ�spring��������
	Servlet web�������
	Spring��������
	Spring DAO����
	Spring web�������
	Spring test �������

4.��ɱҵ�����

5.DAO������뿪�����ӿ����+SQL��д����
	���ݿ����
	DAO��ʵ��ͽӿڱ���
	����myBatisʵ��DAO
		myBatis�ٷ��ĵ���http://www.mybatis.org/mybatis-3/zh/index.html
		mybatis-config.xml
		XML�ṩDAO��SQL����
	myBatis����Spring
		spring-framework-reference
	DAO�㵥Ԫ���Ա���������Ų�

6.��ɱService�ӿ����

7.ʵ��SeckillService�ӿ�
	���б������쳣ת��Ϊ�������쳣 ��
	ö�� ��

8.����Spring�й�Service��������ʵ�֣�
	Spring IOC������⣺
		���󹤳�+��������  ----->  һ�µķ��ʽӿڣ���ȡ����ʵ����
	��Ŀҵ�����������
		SeckillService �����ڣ� SeckillDao + SuccessKilledDao �����ڣ�SqlSessionFactory �����ڣ�DataSource...
	IOCʹ�ã�
		XML���� -----> package-scan -----> Annotationע�⣨@Service   @Autowired��

9.Spring����ʽ��������
	���������������
		<bean id="transactionManager" class="org.springframework.jdbc.datasource.DataSourceTransactionManager">
	ʹ��ע��������������Ϊ��
		<tx:annotation-driven transaction-manager="transactionManager"></tx:annotation-driven>
	@Transactional

10.���ɲ���Service�߼�
	logback.xml ��

11.ǰ�˽������ *****

12.Restful�ӿ����

13.��������SpringMVC���

14.ʹ��SpringMVCʵ��Restful�ӿ�

15.����bootstrap����ҳ��ṹ
	http://www.runoob.com/bootstrap/bootstrap-environment-setup.html

16.�����߼����
	cookie��¼������
		http://www.bootcdn.cn/
		����js�ļ�ʱcharset="GBK"���������������
	��ʱ����
		countdown����ʹ��
	��ɱ����
		Timestamp nowTime = new Timestamp(System.currentTimeMillis());

17.��Ŀ�ܽ�

