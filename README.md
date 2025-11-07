# af75be
# af75be04cf68b982c436dad4a7925954

## mo
### e38282
### mo_text
も (mo) 82 26 130
```text
も
```

### mo_bash
echo -en "\xe3\x82\x82";
```bash
echo -en "\xe3\x82\x82";
```

### mo_golang
package main;import("fmt");func main(){var byteArray []byte=[]byte{0xe3, 0x82, 0x82};var string string=string(byteArray);fmt.Printf("%s\n",string)}
```golang
package main;import("fmt");func main(){var byteArray []byte=[]byte{0xe3, 0x82, 0x82};var string string=string(byteArray);fmt.Printf("%s\n",string)}
```

### mo_kotlin
fun main(){val byteArray:ByteArray=byteArrayOf(0xe3.toByte(),0x82.toByte(),0x82.toByte());val string:String=String(byteArray,charset("UTF-8"));println(string)}
```kotlin
fun main(){val byteArray:ByteArray=byteArrayOf(0xe3.toByte(),0x82.toByte(),0x82.toByte());val string:String=String(byteArray,charset("UTF-8"));println(string)}
```

### mo_rust
```rust
use std::borrow::Cow;fn main(){let byte_array:&[u8]=&[0xe3, 0x82, 0x82];let string:Cow<'_,str>=String::from_utf8_lossy(byte_array);println!("{}", string);}
```
