# কন্সট্যান্টস

গো তে কনস্ট্যান্টস ডিফাইন করার জন্য `const` কিওয়ার্ডটি ব্যবহার করি আমরা । এই কিওয়ার্ডটির পর কনস্ট্যান্ট এর নাম এবং তারপর এটির ভ্যালু এ্যাসাইন করি । 

আমরা যেসব জায়গায় `var` ব্যবহার করতে পারি তার সব জায়গাতেই কনস্ট্যান্ট ডিফাইন করা সম্ভব । 

```go
package main

import "fmt"

// কনস্ট্যান্ট ডিক্লেয়ারেশন
const s string = "constant"

func main() {
	fmt.Println(s)
	const n = 500000000
	fmt.Println(n)
}

```