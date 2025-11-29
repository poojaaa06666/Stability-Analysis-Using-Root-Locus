# Stability Analysis using Root Locus
## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software

## Theory:
<img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/b58c4cdf-be07-444f-97d2-1872fafe7fa2" />
<img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/3493953f-1bfa-4f5a-9752-3a18b1b360f6" />
<img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/cd646d0c-0918-4a61-833f-755838bf152e" />
<img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/49a11d3b-1951-429b-994c-ad86a5d8772e" />


## Procedure:
	Open MATLAB software
	Open a new script file.
	Type the program.
	Save and Execute the program.
	Click on the crossing point of the root locus to find the value of K and poles at the crossing point.
	From the value of K, analyse the stability.

## Program: 

```
num=[1]
den=[1 15 50 0]
sys=tf(num,den)
rlocus(sys)
[k poles]=rlocfind(sys)
```

## Output:

<img width="699" height="626" alt="image" src="https://github.com/user-attachments/assets/efb210b9-801d-4a1a-b603-66c56093cb8b" />

## Result:
Thus the root locus for the given transfer function was drawn and verified using MATLAB. The conditions for stability is 744.551 .
