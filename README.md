# tugas-kurs-mata-uang
<!DOCTYPE html>
<html lang="en">
<head>
    <style>
    table, th, td {
        border: 2px solid black;
      }
      
</style>
    <title>Nilai tukar rupiah</title>     
</head>
<body>
  <div class="center">
  <button onclick="hello()">tekan saya</button>
    <table style="width:50%">
        <tr>
          <th>masukan nilai</th>
          <th>value</th> 
          <th>nilai rupiah</th>
        </tr>
        <tr>
            <td><input onkeyup="kurs()" style="width: 90%" placeholder="Masukan Nilai" type="text" name="nilai" id="nilai"></td>
            <td>
            <select onchange="kurs()" id="kurs" style="width: 80%"
              <option value="0">ubah kurs</option>
              <option value="1">Dollar US</option>
              <option value="2">Dollar singapore</option>
              <option value="3">Ringgit Malaysia</option>
              <option value="4">Yen Jepang</option> 
              <option value="5">euro</option>
              <option value="6">Riyal arab saudi</option>
            </td></select>
            <td><input type="text" disabled="" id="rupiah" placeholder="Nilai Rupiah" style="width: 90%" name="rupiah"></td>
          </tr>
        </table>
    
  </div>
</body>
        <script type="text/javascript">
          function hello(){
            alert ("Selamat Datang");
          }
	function kurs() {

		let k = document.getElementById("kurs").value;

		if (k == 1) {
			input = document.getElementById("nilai").value;
			nilai = 14.161,75 ;
			hitung = nilai * input;
			document.getElementById("rupiah").value = hitung;
		}else if (k == 2) {
			input = document.getElementById("nilai").value;
			nilai = 10.503,72;
			hitung = nilai * input;
			document.getElementById("rupiah").value = hitung;
		}else if (k == 3) {
			input = document.getElementById("nilai").value;
			nilai = 3.435,00 ;
			hitung = nilai * input;
			document.getElementById("rupiah").value = hitung;
		}else if (k == 4) {
			input = document.getElementById("nilai").value;
			nilai = 135,13 ;
			hitung = nilai * input;
			document.getElementById("rupiah").value = hitung;
		}else if (k == 5) {
			input = document.getElementById("nilai").value;
			nilai = 16.760,98;
			hitung = nilai * input;
			document.getElementById("rupiah").value = hitung;
		}else if (k == 6) {
			input = document.getElementById("nilai").value;
			nilai = 3.775,88;
			hitung = nilai * input;
			document.getElementById("rupiah").value = hitung;
		}
	}
    
</script>

</html>
