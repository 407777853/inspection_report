### ��Ҫ�ļ����ܣ�
    inspection_report.py ������
    config.yml �����ļ�
    templates ģ��Ŀ¼�ļ�
    pcinfo.txt ����IP���˿ڡ��û������롢����5��


### ����
    ����pcinfo.txt�ļ���д������IP���˿ڡ��û������롢����5�У��Կո�ָ���ÿ̨����һ��
    ����192.168.1.1 22 root password db
    ����inspection_report.py�����ȴ�ִ�н��������н��������ն˴�ӡ���н�������ʾ��ʱ

### ������
    ���н����󣬻�����html_dirĿ¼����Ŀ¼�а�����Ѳ���¼����ϸ����
    ���ɵ�����Ŀ¼��md_dir������ʱ�ļ�

> ����Ҫ�ֶ������ʱĿ¼��������ÿ������ǰ���Զ������ЩĿ¼

### ��������
    python 3
    import paramiko
    import traceback
    import socket
    import re
    import markdown
    import logging
    import yaml
    import time
    import os
    import shutil
    from multiprocessing import Pool
    