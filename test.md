# find�F���p����
linux�R�}���h��find�̊��p����̊o������

### Description
find�͌����R�}���h�ł��邪�A�@�\�����͂Ȃ��ߏd�󂷂�B�I�v�V���������G�Ȃ��߁A���ׂĎg�����ۂ̎�����c���Ă���B

## ����

* �t�@�C�����������A���k����
```
find ./ -name "*.htm*" -exec tar rvf /tmp/YYYYMMDD.tar {} \;
```

* ���������̃t�@�C��������
```
find ./ \( -iname '*css' -or -iname \*html \) -print
```

