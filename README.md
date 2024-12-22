# Методы для работы с массивами в JavaScript

В этом файле подробно описаны основные методы для работы с массивами в JavaScript, с примерами их использования. Все примеры показывают как этот метод будет работать на практике.

---

## **1. pop()**
Удаляет последний элемент массива и возвращает его.

**Пример:**
```javascript
let arr = [1, 2, 3];
let lastElement = arr.pop();
console.log(arr); // [1, 2]
console.log(lastElement); // 3
```

---

## **2. push()**
Добавляет элемент в конец массива.

**Пример:**
```javascript
let arr = [1, 2];
arr.push(3);
console.log(arr); // [1, 2, 3]
```

---

## **3. shift()**
Удаляет первый элемент массива и возвращает его.

**Пример:**
```javascript
let arr = [1, 2, 3];
let firstElement = arr.shift();
console.log(arr); // [2, 3]
console.log(firstElement); // 1
```

---

## **4. unshift()**
Добавляет элементы в начало массива.

**Пример:**
```javascript
let arr = [2, 3];
arr.unshift(1);
console.log(arr); // [1, 2, 3]
```

---

## **5. concat()**
Создаёт новый массив, объединяя существующие.

**Пример:**
```javascript
let arr1 = [1, 2];
let arr2 = [3, 4];
let newArr = arr1.concat(arr2);
console.log(newArr); // [1, 2, 3, 4]
```

---

## **6. slice()**
Возвращает новый массив, содержащий часть исходного.

**Пример:**
```javascript
let arr = [1, 2, 3, 4, 5];
let subArr = arr.slice(1, 4);
console.log(subArr); // [2, 3, 4]
```

---

## **7. join()**
Преобразует элементы массива в строку, разделённую указанным символом.

**Пример:**
```javascript
let arr = [1, 2, 3];
let str = arr.join('-');
console.log(str); // "1-2-3"
```

---

## **8. includes()**
Проверяет, содержит ли массив указанное значение.

**Пример:**
```javascript
let arr = [1, 2, 3];
console.log(arr.includes(2)); // true
console.log(arr.includes(4)); // false
```

---

## **9. indexOf()**
Возвращает индекс первого вхождения элемента. Если элемент не найден, возвращает `-1`.

**Пример:**
```javascript
let arr = [1, 2, 3, 2];
console.log(arr.indexOf(2)); // 1
console.log(arr.indexOf(4)); // -1
```

---

## **10. splice()**
Добавляет, удаляет или заменяет элементы массива.

**Пример:**
```javascript
let arr = [1, 2, 3, 4];
arr.splice(1, 2, 5, 6);
console.log(arr); // [1, 5, 6, 4]
```

---

## **11. toString()**
Преобразует массив в строку.

**Пример:**
```javascript
let arr = [1, 2, 3];
console.log(arr.toString()); // "1,2,3"
```

---

## **12. reverse()**
Переворачивает массив в обратном порядке.

**Пример:**
```javascript
let arr = [1, 2, 3];

