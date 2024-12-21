sadklkdslkf
dkflksdlf

![image](firefox_q4GnTG3lIT.png)


```
public static int Value
{
    get => _value;
    set
    {
        _value = value;
        
        if (_value < 0)
            _value = 0;
        
        ValueChange?.Invoke(_value);
    }
}
```


