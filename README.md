# js-lab-106
### Lab106 Function: Fundamental1
ให้เรียกใช้ฟังก์ชัน ask โดย 
- Parameter ตัวแรกเป็น 'Do you agree?'
- Parameter ตัวที่สองเป็นฟังก์ชันที่เมื่อทำงานแล้วจะ alert คำว่า “I’m agree with you ?”
- Parameter ตัวที่สามเป็นฟังก์ชันที่เมื่อทำงานแล้วจะ alert คำว่า “whyyyyyyy !”

```JavaScript
function ask(question, yes, no) {
  if (confirm(question)) yes();
  else no();
}
```
