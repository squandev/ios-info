# 📌 Гайд по неймингу в коде (общие рекомендации + Swift)

## 1. Общие принципы нейминга
✅ **Выбирайте осмысленные и понятные имена**
- **Плохо**: `a`, `data`, `temp`, `doSomething()`
- **Хорошо**: `userId`, `invoiceList`, `calculateTax()`

✅ **Избегайте сокращений и непонятных аббревиатур**
- **Плохо**: `usrAddr`, `calcTtl`, `prcReq()`
- **Хорошо**: `userAddress`, `calculateTotal()`, `processRequest()`

✅ **Не дублируйте информацию**
- **Плохо**: `userObject`, `productDataList`
- **Хорошо**: `user`, `productList`

✅ **Не добавляйте тип в название переменной**
- **Плохо**: `var userArray: [User]`
- **Хорошо**: `var users: [User]`

---

## 2. Переменные и константы
### ✅ Используйте существительные для объектов и данных
```swift
let user: User
var userList: [User]
let maxConnections = 10
```

### ✅ Булевы переменные начинайте с `is`, `has`, `should`
```swift
var isUserLoggedIn = false
var hasAccess = true
var shouldShowWarning = false
```

### ✅ Используйте осмысленные суффиксы
```swift
var userCount = 10
var usernameTextField: UITextField
var userDictionary: [String: User]
```

---

## 3. Функции и методы
### ✅ Функции должны содержать глагол
```swift
func fetchUserData()
func saveDocument()
func validateEmail()
func startAnimation()
```

### ✅ Используйте понятные аргументы
```swift
func calculateTax(for amount: Double) -> Double
func sendNotification(to user: User)
func loadImage(named name: String)
```

### ✅ Избегайте дублирования информации
```swift
func setTitle(_ title: String)  // ✅ Хорошо
func setTitle(titleString: String)  // ❌ Плохо
```

### ✅ Используйте `mutating` для изменяющих объект методов
```swift
mutating func updateProfile(with newProfile: UserProfile)
```

### ✅ Функции, работающие с асинхронным кодом
```swift
func fetchUsers() async throws -> [User]
func loadProfileImage() async -> UIImage?
```

---

## 4. Классы, структуры, протоколы и перечисления
### ✅ Классы и структуры — существительные в `PascalCase`
```swift
class UserProfile {}
struct PaymentInfo {}
```

### ✅ Протоколы — отражают поведение (`-able`, `-ing`)
```swift
protocol Printable {}
protocol Draggable {}
protocol DataLoading {}
```

### ✅ Перечисления — описывают состояние или категории
```swift
enum UserStatus {
    case active
    case inactive
    case banned
}
```

---

## 5. Файлы и модули
### ✅ Файл должен соответствовать классу или структуре внутри
- `UserProfile.swift` → `class UserProfile {}`
- `PaymentInfo.swift` → `struct PaymentInfo {}`

### ✅ Файл должен отражать свое содержимое
- `NetworkingManager.swift` (а не `Manager.swift`)
- `AuthenticationService.swift` (а не `Auth.swift`)


## 8. Чек-лист перед отправкой кода
✅ **Все переменные, функции, классы имеют осмысленные имена**  
✅ **Следует принятому стилю кодирования (camelCase, PascalCase, SCREAMING_SNAKE_CASE)**  
✅ **Функции содержат глагол и явно описывают, что делают**  
✅ **Булевы переменные начинаются с `is`, `has`, `should`**  
✅ **Файл соответствует содержимому**  

