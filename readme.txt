Git��װ��ɺ�ĳ�ʼ��
1.�� Git Bash
2.�������git config --global user.name "lumicae"
	    git config --global user.email "lumicae@sina.com"
  Git �Ƿֲ�ʽ�汾����ϵͳ�� ������Ҫ��д�û�����������Ϊһ����ʶ
  git config --global ������ʾ ���������е�Git�ֿⶼ��ʹ���������
һ�������汾��
   cd D:
   cd gitRepostiory
   mkdir testgit
   cd testgit
   pwd  //���/d/gitRepository/testgit,pwd����������ʾ��ǰ��Ŀ¼
 1.ͨ������git init ��Ŀ¼testgit���git���Թ���Ĳֿ⣬��ʱtestgitĿ¼�»����һ��.git��Ŀ¼��.git��Git������
   ����汾�ģ���Ҫ���ĸ��ļ���
 2.���ļ���ӵ��汾����testgit�´����ļ�readme.txt,����һЩ���ݲ�����
   ��һ���� ʹ������ git add readme.txt��ӵ��ݴ�������
   �ڶ����� ʹ������ git commit -m "readme.txt�ύ" ���ļ��ύ���ֿ� -m ����ַ������ύ��ע��
   �������� ʹ������ git status �鿴�Ƿ��ļ�δ�ύ
   ���Ĳ��� �޸�readme.txt�ļ����ݣ�����ʹ��git status�鿴���
   ���岽�� ʹ�� git diff readme.txt�鿴readme.txt�ļ����׸���ʲô����
   �������� ʹ������ git add readme.txt,git commit -m "�������ݵ���������"
�����汾����
   1.������readme.txt�ļ������޸� ��Ȼ��add �� commit
   2.�����Ѿ���readme.txt���������޸ģ�����ʹ������ git log�鿴��ʷ��¼����ʾ�ļ�¼�����У��汾�š����ߡ�ʱ�䡢ע��
   3.ʹ������ git log --pretty=oneline������ʾ��־���ݣ��汾�ź�ע��
   4.���˰汾��������ַ�ʽ��git rest --hard HEAD^,^��ʾ���˵��ϸ��汾��������˵�ǰn���汾�Ļ�������n��^; git reset --hard HEAD~100
   5.����ʹ������ cat readme.txt�鿴readme.txt�ļ�������
   6.���˵����°汾��git reset --hard �汾��
   7.ʹ�����git reflog ��ȡ�����а汾��
   8.���ڵ��ļ��������°汾�ˡ�
���� ��⹤�������ݴ���������
   1.�޸�readme.txt ���½��ļ�test.txt����git status�鿴״̬
   2.