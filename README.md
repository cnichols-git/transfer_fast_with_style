# transfer_fast_with_style  
## This is only for single files and not directories
This will transfer a file with a progress bar  
  
Receiving computer:  
nc -l -p 7000 > /home/chris/Video/movie.mkv  
  
Sending computer:  
pv movie.mkv | nc -N 10.0.0.2 7000  

<img width="1386" height="66" alt="image" src="https://github.com/user-attachments/assets/ceb58d87-df03-40b6-a10b-813f93d5ab16" />

## This will give a percentage of completion
rsync -avhP Insomnia/ 10.0.0.2:/home/chris/Video/  

<img width="1380" height="146" alt="image" src="https://github.com/user-attachments/assets/e34c1119-8bdb-46bb-9a31-2a46731faba2" />
