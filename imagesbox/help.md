# ͼƬ�鿴������,���

## ����

linkTitle: ���ͼƬ��ʾ��Ϣ��Ĭ��Ϊ '����鿴ԭͼ'  

direction: ��ͷ��ʾ����ˮƽ���� (horizontal) �ʹ�ֱ���� (vertical)��Ĭ��Ϊ 'horizontal'

## ���ʹ��

1������

```
<link rel="stylesheet" href="css/jquery.imagebox.css" />
<script type="text/javascript" src="js/jquery.imagebox.js"></script>
```

2��ʹ��

```
��ͼ
<a  id='id1' href="javascript:;"><img width="100" height="50" src="1.jpg"></a>
$('#id1').imagebox();
���
<a  id='id2' href="javascript:;"><img width="100" height="50" src="1.jpg"><img width="100" height="50" src="1.jpg"></a>
$('#id2').imagebox();
����,��ͼ��Ч
<a  id='id3' href="javascript:;"><img width="100" height="50" src="1.jpg"><img width="100" height="50" src="1.jpg"></a>
$('#id3').imagebox({
    linkTitle: '�鿴ԭͼ',
    direction: 'vertical' //Ĭ����ˮƽ���Ҽ�ͷ,�����Ǵ�ֱ
});
```
3. ���������jquery��,�������������ʾ,�޸���һЩ����.
