Nama       : Fatur Sakti Arrafi
NIM        : H1D022041
Shift KRS  : A
Shift Baru : E


TUGAS PERTEMUAN 5 : Proses Aplikasi TokoKita

SCREENSHOT APLIKASI:



<h2>a. Proses Login<h2>
User diminta untuk memasukkan email dan password pada halaman/form login.

Kode yang terkait:

Widget _emailTextField() {
    return TextFormField(
      decoration: const InputDecoration(labelText: "Email"),
      keyboardType: TextInputType.emailAddress,
      controller: _emailTextboxController,
      validator: (value) {
        if (value!.isEmpty) {
          return 'Email harus diisi';
        }
        return null;
      },
    );
  }

  Widget _passwordTextField() {
    return TextFormField(
      decoration: const InputDecoration(labelText: "Password"),
      keyboardType: TextInputType.text,
      obscureText: true,
      controller: _passwordTextboxController,
      validator: (value) {
        if (value!.isEmpty) {
          return "Password harus diisi";
        }
        return null;
      },
    );
  }
  
![alt text](https://github.com/fatur251003/LabMobile4_Fatur-Sakti-Arrafi_Shift-E/blob/main/images/Screenshot%202024-10-01%20160626.png)
![alt text](https://github.com/fatur251003/LabMobile4_Fatur-Sakti-Arrafi_Shift-E/blob/main/images/Screenshot%202024-10-01%20160741.png)
![alt text](https://github.com/fatur251003/LabMobile4_Fatur-Sakti-Arrafi_Shift-E/blob/main/images/Screenshot%202024-10-01%20161247.png)
![alt text](https://github.com/fatur251003/LabMobile4_Fatur-Sakti-Arrafi_Shift-E/blob/main/images/Screenshot%202024-10-01%20161410.png)
![alt text](https://github.com/fatur251003/LabMobile4_Fatur-Sakti-Arrafi_Shift-E/blob/main/images/Screenshot%202024-10-01%20161424.png)
![alt text](https://github.com/fatur251003/LabMobile4_Fatur-Sakti-Arrafi_Shift-E/blob/main/images/Screenshot%202024-10-01%20161553.png)
![alt text](https://github.com/fatur251003/LabMobile4_Fatur-Sakti-Arrafi_Shift-E/blob/main/images/Screenshot%202024-10-01%20161723.png)
![alt text](https://github.com/fatur251003/LabMobile4_Fatur-Sakti-Arrafi_Shift-E/blob/main/images/Screenshot%202024-10-01%20161800.png)
