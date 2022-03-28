# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (user){
  if (user.isActive){
    return `Welcome back, ${user.username}!`
  } else {
    return `Hey ${user.username}! Would you like to renew your subscription?`
  }
}
```

| Input | Output |
| ----- | ------ |
|  {username: "scottyboombox", isActive: true}     |  'Welcome back, scottyboombox!'      | 
|  {username: "kylecoberly", isActive: flase}     | 'Hey kylecoberly! Would you like to renew your subscription'       | 
|  {username: "xX_69PrOsNiPeR69_Xx", isActive: false}   | 'Hey xX_69PrOsNiPeR69_Xx! Would you like to renew your subscription?'       | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This program takes an object with the properties of 'username' and 'isActive'. The username property should be a string and the isActive property should be a boolean. If isActive is true it will greet the user, if it is false it will prompt the user to renew their subscription.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
