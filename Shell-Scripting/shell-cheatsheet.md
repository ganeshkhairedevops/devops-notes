# Shell Scripting Cheat Sheet with Examples

## Shebang
#!/bin/bash
# Tells system to use bash interpreter

---

## Variables
NAME="Ganesh"
echo $NAME

---

## Conditional Example
if [ "$NAME" == "Ganesh" ]; then
    echo "Name matched"
fi

---

## Loop Example
for i in {1..5}; do
    echo $i
done

---

## Read User Input
read USERNAME
echo "Hello $USERNAME"

---

## Function Example
greet() {
    echo "Welcome $1"
}

greet Ganesh
