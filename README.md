# QRcode-generator
import qrcode

data = "https://www.openai.com"
qr = qrcode.make(data)
qr.save("openai_qr.png")
print("QR Code saved as 'openai_qr.png'")
