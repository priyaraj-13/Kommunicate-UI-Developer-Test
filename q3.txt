const reverseNum = (num)=>{
    let numStr = num.toString();
    numStr = numStr.split('').reverse().join('')
    return parseInt(numStr)
}


console.log(reverseNum(149))