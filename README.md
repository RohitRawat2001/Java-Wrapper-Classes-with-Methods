# Java-Wrapper-Classes-with-Methods


# Wrapper Classes in Java
Java provides the following wrapper classes:
```java
Boolean
Character
Byte
Short
Integer
Long
Float
Double
Void (Note: Void is a special case and not a wrapper for a primitive type. It's used as a reference type for the void keyword.)
```

# 1. Boolean Wrapper Class
Primitive Type: boolean

# Boolean Methods:
```java
Boolean.TRUE;
Boolean.FALSE;
Boolean.valueOf(boolean b);
Boolean.valueOf(String s);
boolean parseBoolean(String s);
String toString();
boolean booleanValue();
int compareTo(Boolean b);
boolean equals(Object obj);
int hashCode();
```

# 2. Character Wrapper Class
Primitive Type: char

# Character Methods:

```java
Character.valueOf(char c);
char charValue();
boolean isLetter(char ch);
boolean isDigit(char ch);
boolean isWhitespace(char ch);
boolean isUpperCase(char ch);
boolean isLowerCase(char ch);
char toUpperCase(char ch);
char toLowerCase(char ch);
boolean equals(Object obj);
int compareTo(Character anotherCharacter);
int hashCode();
String toString();
```

# 3. Byte Wrapper Class
Primitive Type: byte

# Byte Methods:

```java
Byte.MIN_VALUE;
Byte.MAX_VALUE;
Byte.SIZE;
Byte.BYTES;
Byte.valueOf(byte b);
Byte.valueOf(String s);
byte parseByte(String s);
byte parseByte(String s, int radix);
byte byteValue();
int compareTo(Byte anotherByte);
boolean equals(Object obj);
int hashCode();
String toString();
```

# 4. Short Wrapper Class
Primitive Type: short

# Short Methods:

```java
Short.MIN_VALUE;
Short.MAX_VALUE;
Short.SIZE;
Short.BYTES;
Short.valueOf(short s);
Short.valueOf(String s);
short parseShort(String s);
short parseShort(String s, int radix);
short shortValue();
int compareTo(Short anotherShort);
boolean equals(Object obj);
int hashCode();
String toString();
```

# 5. Integer Wrapper Class
Primitive Type: int

# Integer Methods:

```java
Integer.MIN_VALUE;
Integer.MAX_VALUE;
Integer.SIZE;
Integer.BYTES;
Integer.valueOf(int i);
Integer.valueOf(String s);
Integer.valueOf(String s, int radix);
int parseInt(String s);
int parseInt(String s, int radix);
Integer decode(String nm);
int intValue();
int compareTo(Integer anotherInteger);
boolean equals(Object obj);
int hashCode();
String toString();
String toString(int i);
String toString(int i, int radix);
```

# 6. Long Wrapper Class
Primitive Type: long

# Long Methods:

```java
Long.MIN_VALUE;
Long.MAX_VALUE;
Long.SIZE;
Long.BYTES;
Long.valueOf(long l);
Long.valueOf(String s);
Long.valueOf(String s, int radix);
long parseLong(String s);
long parseLong(String s, int radix);
Long decode(String nm);
long longValue();
int compareTo(Long anotherLong);
boolean equals(Object obj);
int hashCode();
String toString();
String toString(long l);
String toString(long l, int radix);
```

# 7. Float Wrapper Class
Primitive Type: float

# Float Methods:

```java
Float.MIN_VALUE;
Float.MAX_VALUE;
Float.SIZE;
Float.BYTES;
Float.POSITIVE_INFINITY;
Float.NEGATIVE_INFINITY;
Float.NaN;
Float.valueOf(float f);
Float.valueOf(String s);
float parseFloat(String s);
float floatValue();
int compareTo(Float anotherFloat);
boolean equals(Object obj);
int hashCode();
String toString();
String toString(float f);
boolean isNaN();
boolean isInfinite();
boolean isFinite(float f);
```

# 8. Double Wrapper Class
Primitive Type: double

# Double Methods:

```java
Double.MIN_VALUE;
Double.MAX_VALUE;
Double.SIZE;
Double.BYTES;
Double.POSITIVE_INFINITY;
Double.NEGATIVE_INFINITY;
Double.NaN;
Double.valueOf(double d);
Double.valueOf(String s);
double parseDouble(String s);
double doubleValue();
int compareTo(Double anotherDouble);
boolean equals(Object obj);
int hashCode();
String toString();
String toString(double d);
boolean isNaN();
boolean isInfinite();
boolean isFinite(double d);
```

# 9. Void Wrapper Class
Primitive Type: void (Note: Void is not actually a wrapper for a primitive type; it's used as a placeholder for methods that don't return a value.)


# Void Methods:
```java
Void.TYPE;
```
# Additional Notes:
equals(Object obj) and hashCode(): These methods are common across all wrapper classes, and they allow for comparing objects and generating hash codes.

compareTo(T anotherT): This method is used to compare two instances of the same wrapper class. It returns a negative integer, zero, or a positive integer if the object is less than, equal to, or greater than the specified object, respectively.

valueOf(String s) and parseXXX(String s): These methods are used for converting strings to their respective primitive or wrapper types.

# Conclusion
Wrapper classes in Java encapsulate primitive data types into objects and provide a variety of methods to manipulate and interact with these values. These methods include conversion methods, comparison methods, and utility methods that simplify working with primitives in an object-oriented context. Understanding these methods and their usage is essential for effective Java programming.
