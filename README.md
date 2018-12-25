# my-shortcode
short code
kumpulan short code untuk coding ku

$('#is_bayar').on('switchChange.bootstrapSwitch', function(event, state) {
  //console.log(this); // DOM element
  //console.log(event); // jQuery event
  if (state==true) {
    console.log('true');
    $('.jenis_bayar').show();
    $('#id_bayar').prop('required',true);
  } else {
    $('.jenis_bayar').hide();
    $('#id_bayar').prop('required',false);
  }
 // console.log(state); // true | false
});
