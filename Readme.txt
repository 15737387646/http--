��Ŀ�ṹ��
               |-----httpserver   --HttpServer.py�������� 
      http--   |                  --settings (httpserver����)
               |
               |        
               |
               |
               |-----WebFrame   --static(��ž�̬��ҳ) 
                                --views.py   ( Ӧ�ô������)  
                                --urls.py   (���·��)
                                --settings   (�������)
                                --WebFrame.py (���������) 


����:  
     httpserver:
       ��ȡhttp����
       ����http����
       �������͸�WebFrame
       ��WebFrame���շ�������
       ��������֯ΪResponse��ʽ���͸��ͻ���
     
    WebFrame:
       ��httpserver���վ�������
       ������������߼���������ݴ���
           * ��̬ҳ��
           * �߼�����
       ����Ҫ�����ݷ�����httpserver
