---
title: Download Daftar Harga Paper Bag, Tote Bag dan Plastik Bag.
permalink: /download-daftar-harga-paper-bag.html
is_post: true
---

<div class="table-responsive">
<table class="post-tab-1" id="HargaMuslimDewasa">
<thead>
<tr>
  <th style="background: aliceblue;" width="40%"></th>
  <th width="15%">Kecil</th>
  <th width="15%">Sedang</th>
  <th width="15%">Besar</th>
  <th width="15%">Jumbo</th>
</tr>
</thead>
<tbody>
  <tr>
    <td></td>
    <td class="nm">Menarik data..</td>
  </tr>
</tbody>
</table>
</div>
<h3>Ketentuan Produksi</h3>
<ul>
<li>Cetak 1000++ lebih murah, diskon by chat. Boleh beda model.</li>
<li>Cetak plastic 2 sisi tambah 50rb/100pcs dari harga dasar.</li>
<li>Ongkos sablon / cetak plastic dan packaging kertas harga mulai dari 80rb/100pcs.</li>
<li>File gambar yang dikirim ke kami menentukan hasil cetak, harus tajam atau lebih baik gunakan file vektor Corel/AI</li>
</ul>


<script type="text/javascript">
  function showInfo(data, tabletop) {
    /*$.each( tabletop.sheets(), function(i, sheet) {
      $("#table_info").append("<p>" + sheet.name + " has " + sheet.column_names.join(", ") + "</p>");
    });*/
  
  $("#HargaMuslimDewasa tbody").html("");
  $.each( tabletop.sheets("Bag").all(), function(i, bags) {
    var cat_li = $('<tr><td><strong>' + bags.Jenis + '</strong></td>');
  cat_li.append('<td class="nm">' + bags.Kecil + ' </td><td class="nm">'+ bags.Sedang +'</td><td class="nm">'+ bags.Besar +'</td><td class="nm"> ' + bags.Jumbo +'</td></tr>');
    cat_li.appendTo("#HargaMuslimDewasa tbody");
  })
  }
</script>
