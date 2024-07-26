# ME2401-USBJTAG
USB-JTAG/UART

FT2232H����USB�V���A���ϊ����W���[��

<!-- <img src="Image/product-picture_01.jpg" width="500px"> -->

<img src="https://github.com/mar-electronica/ME2401-USBJTAG/blob/work/Image/product-picture_01.jpg" width="500px">

[English README is here.](https://github.com/mar-electronica/ME2401-USBJTAG/blob/main/README-en.md)

# �T�v
<!-- <img src="Image/block-diagram_01.png" width="800px"> -->
<img src="https://github.com/mar-electronica/ME2401-USBJTAG/blob/work/Image/block-diagram_01.png" width="500px">

- FTDI��FT2232H����USB�V���A���ϊ����W���[��
- JTAG��UART���e1ch�����Ɏg�p�\
- JTAG��Vref�d����1.1-5.5V���T�|�[�g
- JTAG-SWD�ϊ����W���[���t��
- [OpenOCD](https://openocd.org/)���g�p����JTAG�f�o�b�K�Ƃ��Ďg�p�\
- UART�̃��W�b�N���x����TTL(1.1-5.5V)��RS-232���T�|�[�g

# �d�l
- USB
  - USB2.0 High Speed 480Mbps
  - �o�X�p���[����
  - Type-C�R�l�N�^
- JTAG
  - 2.54mm 20pin�R�l�N�^
    - 20-pin ARM Standard JTAG�݊�
  - Vref�d��
    - 1.1V-5.5V�͈̔͂Ń��t�@�����X�d�����O�����狟���\
- SWD
  - SWD�ϊ����W���[�����g�p����SWD�ł̐ڑ����\
  - 3�X�e�[�g�o�b�t�@�ɂ��SWDIO�̑o��������
  - 1.27mm 10pin�R�l�N�^
    - Cortex Debug (10-pin)�݊�
  - 2.54mm�s���w�b�_
    - SWDIO/SWCLK/nSRST���T�|�[�g
  - Vref�d��
    - 1.1V-5.5V�͈̔͂Ń��t�@�����X�d�����O�����狟���\
- UART
  - ���W�b�N���x����TTL(1.1-5.5V)��RS-232��r�����p�\
    - �{�[�h��̃s���w�b�_�őI��
  - TTL
    - 2.54mm�s���w�b�_
      - TXD/RXD/RTS/CTS���T�|�[�g
    - �d��
      - 1.8V/3.3V/5V�̓d�����{�[�h��ŋ����\
      - 1.1-5.5V�͈̔͂œd�����O�����狟���\
  - RS-232
    - RS-232�̃��C���h���C�o�E���V�[�o����
- ���@
  - W81mm x D50mm x H35mm

# ���i�\��
## �����i
| #  | ����                            | �� |
|----|---------------------------------|------|
| 1  | ���C�����                      | 1    |
| 2  | ��ʃJ�o�[                      | 1    |
| 3  | ��ʃJ�o�[                      | 1    |
| 4  | JTAG/SWD�ϊ����                | 1    |
| 5  | �i�C�����X�y�[�T�[ M3*5mm       | 4    |
| 6  | �i�C�����X�y�[�T�[ M3*10mm      | 4    |
| 7  | ���b�V���t���l�W M3*30mm        | 4    |
| 8  | �i�b�g M3                       | 4    |
| 9  | �S����                          | 4    |
| 10 | �W�����p�\�P�b�g                | 3    |
| ~11~ | ~USB Type-A to Type-C�P�[�u�� 1m~ | ~1~    |
| ~12~ | ~JTAG 20Pin ���{���P�[�u�� 30cm~  | ~1~    |

## �p�b�P�[�W
- W160mm x D120mm x H20mm

<!-- <img src="Image/package-picture_01.jpg" width="500px"> -->
<img src="https://github.com/mar-electronica/ME2401-USBJTAG/blob/work/Image/package-picture_01.jpg" width="500px">

## �g�����@

TBD


# �g�p���@
## PC�Ƃ̐ڑ�
PC��USB Type-A to Type-C�P�[�u���Őڑ����Ă��������B

<!-- <img src="Image/usage-pc_01.jpg" width="500px"> -->
<img src="https://github.com/mar-electronica/ME2401-USBJTAG/blob/work/Image/usage-pc_01.jpg" width="500px">

## �f�o�C�X�h���C�o�̃C���X�g�[���Ɛݒ�
### �C���X�g�[��
#### Windows
Windows10�ȏ�̃p�\�R���ł́A�f�o�C�X�h���C�o�̓C���X�g�[���ς��A�����ŃC���X�g�[������܂��B

�����ŔF�����Ȃ��ꍇ�́AFTDI�Ђ�HP���h���C�o���_�E�����[�h���ăC���X�g�[�����Ă��������B

[Drivers - FTDI](https://ftdichip.com/drivers/)

#### Linux
Ubuntu 11.10, kernel 3.0.0-19�ȍ~�̃p�\�R���ł́A�f�o�C�X�h���C�o�̓C���X�g�[���ςł��B

### �ݒ�
#### Windows
TBD
[Zadig - USB driver installation made easy](https://zadig.akeo.ie/)

#### Linux
TBD

## JTAG
### OpenOCD
TBD

### GDB����̐ڑ�
TBD

### LED
JTAG�̃A�N�Z�X�ɉ�����LED���_�����܂��B
- ALED(��)

nSRST�A�T�[�g����LED���_�����܂��B
- RLED(��)


## SWD
### SWD�ϊ����W���[���̐ڑ�
TBD

### OpenOCD
TBD

### GDB����̐ڑ�
TBD

## UART
### ���W�b�N���x���̑I��
- TTL(1.1-5.5V)��RS-232��r�����p�\
- �{�[�h��̃s���w�b�_(JP2)�őI��

<!-- <img src="Image/usage-uart_01.jpg" width="500px"> -->
<img src="https://github.com/mar-electronica/ME2401-USBJTAG/blob/work/Image/usage-uart_01.jpg" width="500px">

- TTL�Ƃ��Ďg�p����ꍇ(TBD)
<img src="https://github.com/mar-electronica/ME2401-USBJTAG/blob/work/Image/usage-uart_02.jpg" width="500px">


- RS-232�Ƃ��Ďg�p����ꍇ(TBD)
<img src="https://github.com/mar-electronica/ME2401-USBJTAG/blob/work/Image/usage-uart_03.jpg" width="500px">


### TTL
#### �R�l�N�^
- CN3�̃s���w�b�_�ɐڑ����Ďg�p���܂��B
<img src="https://github.com/mar-electronica/ME2401-USBJTAG/blob/work/Image/usage-uart_04.jpg" width="500px">

#### TTL�g�p���̓d��
- TTL�g�p���̓d����1.1-5.5V�͈̔�
- �{�[�h��̃s���w�b�_(JP1)�őI��
- 1.8V/3.3V/5V�̓d�����{�[�h��ŋ����\
- 1.1-5.5V�͈̔͂œd�����O�����狟���\

<!-- <img src="Image/usage-uart_05.jpg" width="500px"> -->
<img src="https://github.com/mar-electronica/ME2401-USBJTAG/blob/work/Image/usage-uart_05.jpg" width="500px">

##### 1.8V�Ŏg�p����ꍇ(TBD)
<img src="https://github.com/mar-electronica/ME2401-USBJTAG/blob/work/Image/usage-uart_06.jpg" width="500px">

##### 3.3V�Ŏg�p����ꍇ(TBD)
<img src="https://github.com/mar-electronica/ME2401-USBJTAG/blob/work/Image/usage-uart_07.jpg" width="500px">

##### 5V�Ŏg�p����ꍇ(TBD)
<img src="https://github.com/mar-electronica/ME2401-USBJTAG/blob/work/Image/usage-uart_08.jpg" width="500px">

##### �O������d������������ꍇ
<img src="https://github.com/mar-electronica/ME2401-USBJTAG/blob/work/Image/usage-uart_09.jpg" width="500px">

��1.1-5.5V�͈̔͂ł��g�p�������B


### RS-232
#### �R�l�N�^
- CN4��D-Sub 9Pin�R�l�N�^�ɐڑ����Ďg�p���܂��B

<!-- <img src="Image/usage-uart_10.jpg" width="500px"> -->
<img src="https://github.com/mar-electronica/ME2401-USBJTAG/blob/work/Image/usage-uart_10.jpg" width="500px">

### LED
UART�̑���M�ɉ�����LED���_�����܂��B
- ���M�FTXLED(��)
- ��M�FRXLED(��)

<!-- <img src="Image/usage-uart_11.jpg" width="500px"> -->
<img src="https://github.com/mar-electronica/ME2401-USBJTAG/blob/work/Image/usage-uart_11.jpg" width="500px">

# �T�|�[�g
- �����s��񍐂�GitHub��Issues�ł��肢���܂��B
