onst sortBy = function sortBy(value){
  return function compare(a,b) {
    
      if (a[value] < b[value])
        return -1;
      if (a[value] > b[value])
        return 1;
      return 0;
    }
}
 
 // filter
const type = type => arg => arg.type === type;
        
const DATA = { 
  title: 'Menu',
  items: [
    { id: 1, name: 'tacos', type: 'mexican' , price : 50 },
    { id: 2, name: 'burrito', type: 'mexican' ,price : 100 },
    { id: 3, name: 'tostada', type: 'mexican' ,price : 60  },
    { id: 4, name: 'chowmein', type: 'chinese',price : 25 } ,
    { id: 5, name: 'dal makhini', type: 'indian' ,price : 10 },
    { id: 6, name: 'burrito', type: 'mexican',price : 30 },
    { id: 7, name: 'punjabi toast', type: 'indian' ,price : 23  },
    { id: 8, name: 'pizza', type: 'italian' ,price : 50  }
   
  ]
}
