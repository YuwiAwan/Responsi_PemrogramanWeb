<template>
  <link rel='stylesheet' href='https://cdn.jsdelivr.net/npm/bootstrap@4.4.1/dist/css/bootstrap.min.css'>
  <div class="main-body">
   
  </div>
  <section class="contact" id="contact">
    
    <h2>Contact Me</h2>
    <p>Email: yulidwi001@gmail.com</p>
    <p>Phone: (+62)896-1861-8800</p>
    
  </section>
  <section class="form-container">
                <form id="formulir">
                    <div class="form-group">
                        <label for="nama" class="">Nama :</label>
                        <input type="text" id="nama" name="nama" placeholder="Nama Anda" required>
                    </div>
                    <div class="form-group">
                        <label for="tgl_lahir" class="">Tanggal Lahir :</label>
                        <input type="date" id="tgl_lahir" name="tgl_lahir" required> 
                    </div>
                    <div class="form-group">
                        <label>Jenis Kelamin:</label>
                        <input type="radio" id="lakilaki" name="jenis_kelamin" value="Laki-laki" required>
                        <label for="lakilaki">Laki-laki</label>
                        <input type="radio" id="perempuan" name="jenis_kelamin" value="Perempuan">
                        <label for="perempuan">Perempuan</label>
                    </div>
                    <div class="form-group">
                        <label for="pesan">Pesan :</label>
                        <textarea id="pesan" name="pesan" rows="4" required></textarea> 
                    </div>
                    <button type="submit" id="submit">Kirim</button>
                    
                </form>
               
            </section>  
            <section class="result-container">
                <div class="form-result">
                    <textarea id="result" rows="15" cols="20" readonly></textarea>
                </div>
            </section>
          
</template>

<script>
export default {
  name: 'ContactSection'

}



</script>

<style scoped>
.contact {
  text-align: center;
  padding: 100px 0;
  background: #f5f5f5;
}
</style>
