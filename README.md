# Workshop3-assignment

კომპონენტის გარეთ შექმენით ფუნქცია generateUsers, რომელიც დააბრუნებს ათ იუზერს.
კომპონენტის mount-ის შემდეგ  დასეტეთ users სტეიტი იმ მნიშვნელობით რომელსაც აბრუნებს generateUsers. setState(generateUsers())
დაარენდერეთ ეს ლისტი აპლიკაციაში.
ასევე ლისტის ქვემოთ დაამატეთ ღილაკი,რომელსაც დაუმატებთ დაჭერის ივენთს (პრეზენტაციაში შეგხვდებათ სინტაქსი). ღილაკის თითოეულმა დაჭერამ უნდა წაშალოს შემთხვევითი წევრი user მასივიდან.
ასევე ყოველ ჯერზე როცა user-ების მასივი შეიცვლება უნდა განახლდეს საიტის (ტაბის) title შემდეგნაირად: დარჩა x იუზერი (დარჩა 10 იუზერი)