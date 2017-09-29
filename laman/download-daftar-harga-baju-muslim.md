---
title: Download Daftar Harga Konveksi Baju Muslim Terbaru
permalink: /download-daftar-harga-baju-muslim.html
is_post: true
---

<script type="text/javascript">
  var public_spreadsheet_url = 'https://docs.google.com/spreadsheets/d/1gEMw7FskyJBwgfx8TY1jL1MtGroE4REVd4jo2eSkS6U/edit?usp=sharing';
  $(document).ready( function() {
    Tabletop.init( {
      key: public_spreadsheet_url,
      callback: showInfo,
      wanted: [ "MuslimDewasa", "MuslimAnak" ],
      debug: true
      } )
    })

  function showInfo(data, tabletop) {
    $("#table_info").text("We found the tables " + tabletop.model_names.join(", "));
    /*$.each( tabletop.sheets(), function(i, sheet) {
      $("#table_info").append("<p>" + sheet.name + " has " + sheet.column_names.join(", ") + "</p>");
    });
    $.each( tabletop.sheets("Cats").all(), function(i, cat) {
      var cat_li = $('<li><h4>' + cat.Name + '</h4></li>')
      cat_li.append(cat.description);
      cat_li.appendTo("#cats");
    })*/
    $.each( tabletop.sheets("MuslimDewasa").all(), function(i, muslimdws) {
      var cat_li = $('<li><h4>' + muslimdws.Jenis + '</h4></li>')
      cat_li.append("<p>Cost: $" + muslimdws.Harga1 + "</p>");
      cat_li.appendTo("#HargaMuslimDewasa");
    })
  }
  //document.write("The published spreadsheet is located at <a target='_new' href='" + public_spreadsheet_url + "'>" + public_spreadsheet_url + "</a>");    
</script>
