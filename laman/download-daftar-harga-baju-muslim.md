---
title: Download Daftar Harga Konveksi Baju Muslim Terbaru
permalink: /download-daftar-harga-baju-muslim.html
is_post: true
---

<div class="table-responsive">
<table class="post-tab-1" id="HargaMuslimDewasa">
<thead>
<tr>
  <th style="background: aliceblue;" width="40%"></th>
  <th width="60%">Harga</th>
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
<li>Harga diatas adalah harga CMT saja tidak termasuk bahan.</li>
<li>Harga CMT diatas untuk pemesanan 1 model 4 kodi.</li>
<li>Boleh beda warna.</li>
<li>Harga dapat berubah mengikuti model dan quantity pemesanan.</li>
<li>Cancel fee Rp. 180.000,-</li>
<li>Ongkos Pola Rp 500.000 untuk model sulit, model mudah disesuaikan.</li>
</ul>


<script type="text/javascript">
  function showInfo(data, tabletop) {
    /*$.each( tabletop.sheets(), function(i, sheet) {
      $("#table_info").append("<p>" + sheet.name + " has " + sheet.column_names.join(", ") + "</p>");
    });*/
  
  $("#HargaMuslimDewasa tbody").html("");
  $.each( tabletop.sheets("MuslimDewasa").all(), function(i, muslimdws) {
    var cat_li = $('<tr><td><strong>' + muslimdws.Jenis + '</strong></td>');
    cat_li.append('<td class="nm">Rp ' + muslimdws.Harga1 + ' - ' + muslimdws.Harga2 +'</td></tr>');
    cat_li.appendTo("#HargaMuslimDewasa tbody");
  })
  }
</script>
