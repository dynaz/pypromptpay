# pypromptpay

<a href="https://www.buymeacoffee.com/wannaphong"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

[![Build Status](https://travis-ci.org/wannaphong/pypromptpay.svg?branch=master)](https://travis-ci.org/wannaphong/pypromptpay)

QR Code PromptPay in Python 3.

## Install

```
pip install pypromptpay
```

## Using

```python
from pypromptpay import qr_code
qr_code(account,one_time=True,path_qr_code="",country="TH",money="",currency="THB")
```

- account is phone number or  identification number.
- one_time : if you use once than it's True.
- path_qr_code : path save file qr code image.
- country : TH
- money : money (if have)
- currency : THB

return True (if have path_qr_code) or text (if haven't path_qr_code)

## License

Apache Software License 2.0



## Develop

Wannaphong Phatthiyaphaibun (wannaphong@kkumail.com)

## Reference

[แนวนโยบายการใช้มาตรฐาน Thai QR Code ในธุรกรรมการชำระเงิน](https://www.bot.or.th/Thai/FIPCS/Documents/FPG/2562/ThaiPDF/25620084.pdf)
