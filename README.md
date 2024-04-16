# User-Information-to-array-to-convert-


function userInfo() {
        let user = prompt('enter a number')


        let arr = [];

      for (let i = 1; i <= user; i++) {
          arr[i - 1] = i; 
      }

        console.log(arr);

        let into = arr.reduce((prev, curr)=>{
          return prev + curr
        })
        
        console.log('Sum (+) is = ',into);
      

        let sum = arr.reduce((prev, curr)=>{
          return prev * curr
        })
        
        console.log('Into (*) is = ',sum);
      }


      userInfo()
