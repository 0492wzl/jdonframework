how to Debug:
ʹ��eclipse����jdonframework��tesweb:

http://www.jdon.com/jivejdon/thread/38583

1������jdonframwork��Դ�����jboss6��Դ���
2������jboss6��Jdonframework�������μ���ϸ�ĵ�http://www.jdon.com/jivejdon/thread/38522
3����eclipse����jdonframwork��teswebʾ���������Ŀ
4������tesweb��Ŀ������Ŀ���Ա���ɹ����༭tesweb�����ÿ⣬ȷ����·����ȷ����build.xml�ļ������ļ��е�<delete dir="bin"/>��ȡ���������ȡ����ÿ�α���֮�󶼻ὫbinĿ¼ɾ�����Ӷ�����Դ�ļ��Ҳ�����Ӧ��class�ļ�������ʹ��ant����build.xml��ȷ����Ŀ�ܹ��ɹ�����
5����������jboss6��Զ�̵���ѡ�jboss6������Զ�̵���������run.conf.bat�������ļ��У���rem set "JAVA_OPTS=%JAVA_OPTS% -Xrunjdwp:transport=dt_socket,address=8787,server=y,suspend=n"���remȥ������suspend=n��Ϊsuspend=y�����棬����jboss����ʱjboss����Listening for transport dt_socket at address: 8787��ֹͣ���ȴ�eclipse��������
6������eclipse�������ԣ�debug configration-��remote Java application-��˫��-������name��webtest��connection type��standard(socket attach), host:localhost,port: 8787
allow termination of remote vm:ture.�������ԣ��ȴ�jboss������ϣ�������������jboss����