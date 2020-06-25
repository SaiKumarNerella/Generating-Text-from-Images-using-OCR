# Generating-Text-from-Images-using-OCR

This Project is a document layout analysis and optical character recognition application in Python. It is able to automatically outline a document
image's contents, distinguish between graphics and text and perform OCR over the latter. It consists of two stages first Image preprocessing
and recognition of text from the Image.
Libraries Used: Pytesseract,cv2,imutils,Numpy.

[Download Tesseract from here](https://github.com/UB-Mannheim/tesseract/wiki)<br>

Every Image will be processed with below steps to reterive the text : <br>

1.Image will be rescaled to gray scale.
2.Shadows will be removed if there are any.
3.Removal of noise in the image .
4.Image thresholding.
5.Optical Character recognition to retrive the text.

# Sample Input Image

 [ ](Input.png)
 
# Sample Processed Image 

 [ ] (Intermediate.png)
 
 
# Sample Output Text

'S Superstore',
 '',
 'wanna nave TRONSACTION RECORD =~=-=---°7°""',
 'GLOBAL PAYHENTS MERCHANT # 4765085',
 'Atlantic Superstore',
 'Halifax NS',
 'STORe 00369 REG 3',
 '# 39900',
 'a RETAIN THIS COPY FOR YOUR RECORDS',
 'urchas',
 'cea EXP 44/ax',
 'REF t — TSO/ACT RESP',
 'QNooooooo000 ark',
 'DATE TIME AROUNT |',
 '04/21/2020 17:54:03 $ 200.36 CAD',
 'NOT COMPLETED',
 '',
 'BARRINGTON STREET SUPERSTORE',
 '(902) 492-3240',
 '',
 '2020/04/21 Debra 246 03 0899 17:54',
 '21-GROCERY',
 '',
 '(2)05800031344 =PALMOLIVE LEMON HARJ',
 '',
 '2 @ $3.79 7.58',
 '',
 '6030305099 PC COMP PNCK WRU 2.49',
 '(106038399246 =NN CHIPS ALL DRS Hyas',
 '(1308038399254 NN CHIPS REGULAR HwRJ',
 '',
 '$1.79 ea or 2/83.00 KB',
 '',
 '28 2/83.00 3.00',
 '(2)06700000897 COKE DIET HARJ',
 '',
 '2:9 30.99 1,98',
 '',
 'DEPOSIT 1',
 '',
 '2980.10 0.20',
 'oogese02i50 = SING BHUJIA 1',
 '',
 'eso4oogqoo77 H ALU BHUJIA HARI §=—-3,99',
 '22-DAIRY',
 '06038307800 PC YOG NATURAL wry 2.99',
 '(2y96038366414 LARGE EGGS HRS',
 '263.79 7.58',
 '06036387327 ~=PC YOGOURT 3% WR = 2,99',
 '06560400475 LBRT GRK LACT FR wry «= 4,99',
 '(8)06820075¢15 | ASTRO BALKAN WRJ',
 '8 4 $3.99 31.92',
 '23-FROZEN',
 '06038316451 PC FZ COCONUT WRI = 4,99',
 '27-PRODUCE',
 'dsessqcg0z6 PEPRS THAT RED = iy Sg, 99',
 'tsoesieza PC SALTED PEANUT yay 3.199',
 'g6c3eate6s9 © PCO MUSH SLC 227 gy 39)',
 '',
 '(306038388690 © GARLIC 3 CT WRU aa',
 '2 $0.99',
 '',
 '(4706148303301 + ONION YELLOW MR aa',
 '46 $2.99',
 '',
 '4046 AVOCADO SMALL 4g "1.36',
 '',
 '$2.29 ea or 2/$4.00 ’',
 '10 @ 2/84.00 Ke'



