# ������������� Liquibase � Gradle

						Important!
����� �������� �� ��������� ������, ������ ���� ���������� Gradle
� ��������� ���������� � Path. ������� � ������� gradle -v ������ ��������
������ Gradle � ������ Java.

1. �������� � PostgreSQL ������� ���� ������ test

1. ����� ��������� ������, ����� ��������� �������
 
		gradle liquibaseUpdate
		
� ���� ������ test ������ ��������� ������� PERSON,
� ����� 2 ��������� ������� ������� Liquibase

1. ����� ������� ����� (rollback), ��������� � ��������� ������

		gradle liquibaseRollback

1. ��� ������ � ������� �������� ������ liquibaseUpdate
����������� ������������� ��� ������� gradle
