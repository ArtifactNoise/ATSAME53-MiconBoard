# ATSAME53-MiconBoard
ATSAME53 マイコン開発ボード



![TOP img]](img/Resized/02.jpg)

# ■ これは何？

Microchip(旧Atmel)社が販売している 32bit ARM Cortex-M4Fコアを搭載したATSAME53を、
使いやすい様に、電源や水晶等の外部回路を搭載し、ユニバーサル基板で開発が可能にしました。

純粋なマイコン開発を行う際にオススメです。

# ■ スペック

CPU:    ATSAME53
CORE:   ARM Cortex-M4F
Program Memory: 512 KB
Deta Memory:    192 KB
Max Clock:  120 MHz
SERCOM(UART,I2C,SPI): x6
USB(Full-Speed):    x1

# ■ 基板仕様

入力電源: 3.3V 
クロック: 基板上に32.768KHz搭載
GPIO: SERCOMを基準に配置

ライターは安価なMPLAB SNAPを想定したピン配列になっています。
以前はPIC用に作られていたMicrochipのライターも、今ではAtmelのARMコアのライターとしても使用できます。
PIC-Kit4とSNAPに対応し、SWD端子を用いてご利用中のデバック環境でも開発ができます。

