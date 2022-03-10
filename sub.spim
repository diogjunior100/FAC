.data
.text
	main:
	
	li $v0, 5
	syscall
	move $t0, $v0
	
	li $v0, 5
	syscall
	move $t1, $v0
	
	sub $s0, $t1, $t0
	
	li $v0, 1
	move $a0, $s0
	syscall
	
	li $v0, 10 #finalizar o programa
	syscall
	
	