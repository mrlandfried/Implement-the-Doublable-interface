 

Some objects can be doubled, for example a bank account. The result would be a bank account with twice the balance. Some objects can't be doubled. For example, there is no double of a dime coin—no twenty cent coin exists.

The Doublable interface specifies a method for making an object that is double of the current one. It should only be implemented by classes for which doubling makes sense.

Your job is to modify the Word class so that it implements the Doublable interface. Doubling a word should repeat its text. For example,

```
new Word("Java").makeDouble()
```

should produce a Word object with text "JavaJava".