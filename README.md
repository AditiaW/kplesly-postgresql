### Aplikasi Flask Menggunakan PostgreSQL

1. **Clone Repository**
   ```bash
   git clone https://github.com/AditiaW/kplesly-postgresql.git
   cd kplesly-postgresql
   ```

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```
   atau
   ```bash
   python -m pip install -r requirements.txt
   ```

3. **Setup Database URL**
   Dalam file `app.py`, atur URL database Anda menggunakan `app.config['SQLALCHEMY_DATABASE_URI']`.
   ```python
   app.config['SQLALCHEMY_DATABASE_URI'] = 'postgresql://username:password@localhost/database_name'
   ```
   Gantilah `username`, `password`, dan `database_name` sesuai dengan pengaturan database Anda.

4. **Menjalankan Aplikasi Secara Lokal**
   ```bash
   python app.py
   ```

Dengan langkah-langkah di atas, Anda dapat menjalankan aplikasi Flask Anda yang menggunakan PostgreSQL secara lokal. Pastikan untuk mengganti pengaturan database dengan pengaturan yang sesuai dengan database Anda.
