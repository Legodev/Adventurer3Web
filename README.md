# Python��Adventurer3�𐧌�
FlashForge��Adventurer3�𐧌䂷��v���O�����B

�ŏI�I�ɂ́A���[�J���G���A�ɂ���Adventurer3���A�O���ɂ���X�}�t�H�Ő��䂵�����B

���߂Ă�Python�v���O�����Ȃ̂ŁA�i�K�I�ɍ쐬���Ă����\��B

## ��1�i�K
���[�J���G���A���ɂ���}�V���̃R���\�[����ʂ���̐���B

����ł���R�}���h�́A�@��̃X�e�[�^�X�m�F�A�ً}��~�A�����~�B

�����ł̖ړI�́A�ȑOC#�ō쐬����Adventurer3�̐���v���O�����̈ꕔ��Python�ɈڐA���A�n�߂��΂����Python�̃v���O���~���O�ɂȂ�邱�ƁB

- �@�\�T�v<br>
Console.py��Adventurer3��IP�A�h���X�������ɋN������ƁA'> '�ŃR�}���h���͑҂��ɂȂ�B<br>
�����ł́Ap�As�Ajobstop�Aq�����͂ł��A���ꂼ��A�@��̏�Ԋm�F�A�ً}��~�A�����~�A�v���O�����I�������s�����B
- �v���O�����̍\��<br>
Console.py���A�v���P�[�V�����̋N�_�ƂȂ郂�W���[���B<br>
Adventurer3/Controller.py���AAdventurer3�Ƃ̒ʐM���s���ʐM���W���[���B

## ��2�i�K
���[�J���G���A���ɂ���}�V����web�x�[�X�ł̊Ď�

�Ď��Ώۂ́A�}�V���̃X�e�[�^�X�Ɠ����J�����B

�����ł̖ړI�́ARaspberry Pi+Python���g���AWeb�x�[�X�ł�Adventurer3�Ď��@�\���쐬���邱�ƁB

- �@�\�T�v<br>
Raspberry Pi�ŋN����Ahttp://Raspberry Pi��IP:8088 �ɃA�N�Z�X���邱�ƂŁA�T�[�o�[�ɐڑ��B<br>
IP�A�h���X�w���ʂƋ@���ԕ\����ʂ�2�̉�ʂō\�������B
  - IP�A�h���X�w����<br>
Adventurer3��IP�A�h���X���w�肷��B
  - �@���ԕ\�����<br>
�ڑ����Ă���Adventurer3�̏�ԂƓ����J�����ŎB�e������Ԃ�\������B
- �v���O�����̍\��<br>
Adventurer3/views.py��IP�A�h���X�w���ʁE�@���ԕ\����ʂ𐧌䂷�邽�߂̃R�[�h�B<br>
static�ȉ��̃t�H���_�ɓ����Ă���̂́Ahtml�Ƃ���Ɋ֘A����t�@�C���Q�B<br>
static�ȉ��́A��{�I�ɁAVisual Studio��Python��Web�v���W�F�N�g��V�K�ɍ쐬�����ۂɎ�荞�܂ꂽ�t�@�C���ɂȂ�B<br>
static/scripts/update.js�͋@���ԕ\����ʂŁAAdventurer3�̏�Ԃ��T�[�o�[���ɖ₢���킹���邽�߂̃X�N���v�g�������Ă���B<br>
InServer.py��Web�T�[�o�[���N�����邽�߂̋N�_�ƂȂ郂�W���[���B

### �N�����@
Raspberry Pi�Ƀt�@�C���ނ������Ă����āA`Python3 InServer.py`�ŋN���B<br>
�z�X�g���A�|�[�g�́A���ϐ���SERVER_HOST�ASERVER_PORT�Ŏw��ł���B<br>
�z�X�g���̐ݒ�܂߁A���̂悤�ɋN�������ق���������������Ȃ��B<br>
```sh
export SERVER_HOST=`hostname -I`
Python3 InServer.py
```

# License
This software is released under the MIT License, see LICENSE.txt.