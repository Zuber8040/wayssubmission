
# After debugging the code 
```
  // Debug The Function & Calculate The Answer
    const calculateAnswer = (email) =>
{
const [localPart, domain] = emai.split("@");
const [hostname, ...countryCodes] = domain.split(".");
return `${localPart.length}${hostname.length}${countryCodes.reduce( (a,cc) => a + cc.length, "") }`
}
// localPart email length is 12
// hostname has length of 6 
// countrycode array has 4 length 
// final answer is "12"+"6"+"4" = 163

