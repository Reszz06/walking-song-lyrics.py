import time
import sys

def lirik_januari_final():
    # Bagian Header/Atribusi
    print("=" * 40)
    print("🎶 Glenn Fredly - Januari (Bagian Akhir)")
    print("💻 Created by Resz?!")
    print("=" * 40 + "\n")
    
    time.sleep(1.5)

    # Format: ("Teks Lirik", Kecepatan Ketik, Jeda Setelah Baris)
    lirik = [
        ("Oh kasihku, sampai disini kisah kita", 0.1, 1.2),
        ("Jangan tangisi keadaannya", 0.1, 1.5),
        ("Bukan karena kita berbeda", 0.1, 2.0),
        ("Dengarkan, dengarkan lagu lagu ini", 0.07, 1.2),
        ("Memori rintihan hati", 0.1, 1.5),
        ("Kisah kita berakhir di Januari", 0.15, 3.0)
    ]

    for teks, speed, delay in lirik:
        for karakter in teks:
            sys.stdout.write(karakter)
            sys.stdout.flush()
            time.sleep(speed)
        
        time.sleep(delay)
        print()

    print("\n" + "=" * 40)
    print("Thankhttps://github.com/Reszz06 you bro")
    print("=" * 40)

if __name__ == "__main__":
    lirik_januari_final()
