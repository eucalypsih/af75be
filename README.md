# af75be
# af75be04cf68b982c436dad4a7925954

## de
### e381a7
### de_text
0xe3 0x81 0xa7 で (de) 9 167 
```text
で
```

### de_golang
```golang
package main;import("fmt");func main(){var byteArray []byte=[]byte{0xe3,0x81,0xa7};var stringValue string=string(byteArray);fmt.Printf("%s",stringValue);}
```

### de_rust
```rust
fn main(){let byte_array:&[u8]=&[0xe3,0x81,0xa7];let string_value:std::borrow::Cow<'_,str>=String::from_utf8_lossy(byte_array);println!("{}",string_value);}
```

### de_kotlin
```kotlin
fun main(){val byteArray:ByteArray=byteArrayOf(0xe3.toByte(),0x81.toByte(),0xa7.toByte());val stringValue:String=String(byteArray,charset("UTF-8"));println(stringValue);}
```

## ga
### e3818c
### ga_text
```text

```

### ga_kotlin
```kotlin
fun main(){val byteArray:ByteArray=byteArrayOf(0xe3.toByte(),0x81.toByte(),0x8c.toByte());val stringValue:String=String(byteArray,charset("UTF-8"));println(stringValue);}
```

## k
### e381a3
### k_text
0xe3 0x81 0xa3 っ (k) 15 163 &#12387 &#x3063
```text
っ
```

### k_rust
```rust
use std::borrow::Cow;fn main(){let byte_array:&[u8]=&[0xe3,0x81,0xa3];let string_value:Cow<'_,str>=String::from_utf8_lossy(byte_array);println!("{}",string_value);}
```

### k_kotlin
```kotlin
fun main(){val byteArray:ByteArray=byteArrayOf(0xe3.toByte(),0x81.toByte(),0xa3.toByte());val stringValue:String=String(byteArray,charset("UTF-8"));println(stringValue);}
```

## ni
### e381ab
### ni_text
0xe3 0x81 0xab (ni) 18 170
```text
に
```

### ni_bash
echo -en "\xe3\x81\xab";
```bash
echo -en "\xe3\x81\xab";
```

### ni_golang
package main;import("fmt");func main(){var byteArray []byte=[]byte{0xe3,0x81,0xab};var stringValue string=string(byteArray);fmt.Printf("%s\n", stringValue);}
```golang
package main;import("fmt");func main(){var byteArray []byte=[]byte{0xe3,0x81,0xab};var string string=string(byteArray);fmt.Printf("%s\n", string);}
```

### ni_nodejs
```javascript
const byteArray=[0xe3,0x81,0xab];const string=Buffer.from(byteArray).toString('utf8');console.log(string);
```

### ni_python
```python
byte_array:list[int]=[0xe3,0x81,0xab];string_value:str=bytes(byte_array).decode('utf-8');print(string_value);
```

## ni
### e3838b
### ni_text
0xe3 0x83 0x8b ニ (ni) 25 139
```text
ニ
```

## mo
### e38282
### mo_text
0xe3 0x82 0x82 も (mo) 26 130
```text
も
```

### mo_bash
echo -en "\xe3\x82\x82";
```bash
echo -en "\xe3\x82\x82";
```

### mo_golang
package main;import("fmt");func main(){var byteArray []byte=[]byte{0xe3, 0x82, 0x82};var string string=string(byteArray);fmt.Printf("%s\n",string);}
```golang
package main;import("fmt");func main(){var byteArray []byte=[]byte{0xe3, 0x82, 0x82};var string string=string(byteArray);fmt.Printf("%s\n",string);}
```

### mo_rust
```rust
use std::borrow::Cow;fn main(){let byte_array:&[u8]=&[0xe3,0x82,0x82];let string:Cow<'_,str>=String::from_utf8_lossy(byte_array);println!("{}", string);}
```

### mo_kotlin
fun main(){val byteArray:ByteArray=byteArrayOf(0xe3.toByte(),0x82.toByte(),0x82.toByte());val string:String=String(byteArray,charset("UTF-8"));println(string)}
```kotlin
fun main(){val byteArray:ByteArray=byteArrayOf(0xe3.toByte(),0x82.toByte(),0x82.toByte());val stringValue:String=String(byteArray,charset("UTF-8"));println(stringValue)}
```

### mo_cpp
```cpp
#include <iostream>
#include <array>
#include <string>

int main() {
    // Mendefinisikan array byte dengan ukuran tetap menggunakan std::array
    std::array<unsigned char, 3> byteArray = {0xe3, 0x82, 0x82};

    // Mengonversi array byte ke string
    std::string str(byteArray.begin(), byteArray.end());

    // Menampilkan string
    std::cout << str << std::endl;

    return 0;
}
```
