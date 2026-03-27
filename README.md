# LarsTHE55
import os

def wifi_baglan():
    # Windows netsh komutunu kullanarak bağlanma
    komut = f'netsh wlan connect name="{ad}"'
    os.system(komut)
    print(f"{ad} ağına bağlanma isteği gönderildi.")

# Kullanım
wifi_baglan("Ag_Adiniz", "")
