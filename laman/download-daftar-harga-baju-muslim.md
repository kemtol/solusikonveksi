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









<script type="text/javascript">
  function showInfo(data, tabletop) {
    /*$.each( tabletop.sheets(), function(i, sheet) {
      $("#table_info").append("<p>" + sheet.name + " has " + sheet.column_names.join(", ") + "</p>");
    });*/
    var cat_li = "";
    $.each( tabletop.sheets("MuslimDewasa").all(), function(i, muslimdws) {
      cat_li = cat_li + $('<tr><td><strong>' + muslimdws.Jenis + '</strong></td><td class="nm">Rp ' + parseFloat(muslimdws.Harga1) + ' - ' + parseFloat(muslimdws.Harga2) +'</td></tr>');
      //cat_li.appendTo("#HargaMuslimDewasa tbody");
    })
    $("#HargaMuslimDewasa tbody").html(cat_li)
  
  }  
</script>
