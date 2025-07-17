# 🧠 SkinCodePay

SkinCodePay is an innovative payment app that uses a scannable tattoo as a visual authentication method to make payments via Pix or QR Code, integrating layers of security and automation with banking APIs.

## 🚀 Features

- Custom tattoo scanning with visual recognition technology
- Pix and QR Code payment generation
- Integration with banking APIs (e.g., Nubank, Santander)
- Multi-step anti-fraud validation
- Transaction recording with timestamp
- Compatible with Android devices

## 🔒 Security — 14 Layers of Protection

1. Cryptographic validation of the tattoo pattern
2. Comparison with a locally stored secure hash
3. Biometric authentication (if available)
4. Geolocation at the time of the transaction
5. Double verification via banking API
6. End-to-end encryption of payment data
7. Image spoofing detection
8. Transaction tokenization
9. Trusted device registration
10. Suspicious behavior monitoring
11. Automatic session timeout
12. Two-factor validation (optional)
13. Encrypted log backup
14. Logs with local and remote auditing

## 🛠️ Technologies Used

- Python (backend)
- OpenCV / MediaPipe for visual scanning
- Flask + FastAPI for local APIs
- SQLite / PostgreSQL
- Firebase (or Auth0) for optional authentication
- Integration with banking APIs (Pix/QR)
- Android Studio (app interface)
- Git/GitHub for version control

## 🧪 How to Run

```bash
# Clone the repository
git clone https://github.com/yourusername/skincodepay.git
cd skincodepay

# Install the dependencies
pip install -r requirements.txt

# Start the backend
python app.py

👨‍💻 Autor
Breccio, Jose Roberto
LinkedIn — GitHub — Portfólio
