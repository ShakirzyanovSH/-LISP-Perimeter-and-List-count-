(defun Perimeter (x)
  (cond ((null (cdr x)) nil)
        ((zerop (rem (length x) 2)) (cons (* (+ (car x) (cadr x)) 2) (Perimeter (cddr x))))
        (t (Perimeter (cddr x)))))

(defun CalcList(x) 
  (cond ((null x) 0)
        ((listp (car x)) (+ 1 (CalcList (car x)) (CalcList (cdr x)) ))
        (t (CalcList (cdr x))) ))
