# transfer_fast_with_style  

This will transfer a file with a progress bar  
  
Receiving computer:  
nc -l -p 7000 > /home/chris/Video/movie.mkv  
  
Sending computer:  
pv movie.mkv | nc -N 10.0.0.2 7000  

<img width="1386" height="66" alt="image" src="https://github.com/user-attachments/assets/ceb58d87-df03-40b6-a10b-813f93d5ab16" />
