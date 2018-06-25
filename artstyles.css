const heightInput = $('#input_height');
const widthInput = $('#input_width');
const colorInput = $('#colorPicker');

//MAKE A GRID

makeGrid = () => {

  let heightValue = heightInput.val();
  let widthValue = widthInput.val();

  let pixelCanvas = $('#pixel_canvas');
  pixelCanvas.children().remove();



  for (let h = 0; h < heightValue; h++) {
    pixelCanvas.append("<tr></tr>");
  }
  for (let w = 0; w < widthValue; w++) {
    $('tr').append("<td></td>");
  }
}




$('table').on('click', 'td', function() {
  $(this).css('backgroundColor', colorInput.val() );
});




form = $('#sizePicker');
form.submit(function(event) {
    event.preventDefault(); 
    makeGrid();
});
