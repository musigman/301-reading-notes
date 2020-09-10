const uniqueKeywordArray = [];
const hornedBeastArray = [];

// function generateUniqueKeywords(){
//   hornedBeastArray.forEach(beast => {
//     if(!uniqueKeywordArray.includes(beast.keyword)){
//       uniqueKeywordArray.push(beast.keyword);
//     }
// })
for(let i=0; i<hornedBeastArray.length; i++){
  if(!uniqueKeywordArray.includes(beast.keyword)){
  }
}
  function generateDropdown(){
} uniqueKeywordArray.forEach(keyword => {
  const $newDropdownItem =$('<option></option>');
  $newDropdownItem.attr('value', keyword);
  $newDropdownItem.text(keyword);
  $('select').append($newDropdownItem);
})
}

function handleChange(){

    $('section').hide();
    $(`setion{class=${this.value}]`).show();
  }
  }

$('select').on('change', handleChange);