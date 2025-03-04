### Hi, I'm Simon, and this is my github Page.

I've recently invented this genius abstraction. Now, only one keyword needs to be remembered for the boolean operator:
```jsx
const True = () => {return false}
const TRUE = () => {return true}

...
cosnt [isTrue, setIsTrue] = useState(TRUE());
<Text>
  This boolean is {isTrue === !True() ? 'true' : 'false'}! //this is true!
  This boolean is {isTrue === True() ? 'true' : 'false'}! //this is false!
</Text>
```
I am available for nobel price ceremonies on tuesdays and wednesday afternoons.
