# Day4-JS30

filter - loops all items in the array and give it a filter and what to do with it


const fifteen = inventors.filter(function(inventor){
    if (inventor.year >= 1500 && inventor.year < 1600){
        return true;  --this keeps it
    }
})

console.table() shows in console as atable

.map - always gets back the same amount you put in "scans" through the whole array and you get back what you ask from it

.sort - only compares between two different items at a time through the array and reorders them through the logic of 1 and -1.

.reduce - shorthand way of doing for loop?

? true : false -- shorthand if statement 

Array.from = [...nodelist]  -- do the same thing

.split(', ')  // where you would start the split

if (obj![item]) {
    obj[item] = 0           if you dont know if the key exists instead of hardcoding
}
