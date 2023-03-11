# Kuchuk Timofey
## Junior Frontend Developer


* Phone: +375297653663 
* Telegram: @tima_kuchuk 
* Discord: Timofey Kuchuk (@TimaKuchuk) 

## About Myself: 

### I'm a student at Belarusian State University of Informatics and Radioelectronics. My majors are Marketing and Programming. 
### Currently, I focus on creating and testing user interfaces on some websites. I typically use HTML/CSS and JavaScript in the client. 

## Skills and Proficiency: 
* HTML&CSS
* JavaScript Basics
* C++ Basics
* Git, GitHub

## Code example:
### Task: Remove all excess spaces.
```
int main(){
    char c[80];
    printf("Введите предложение: \n");
    gets(c);
    
    if(c[0] == ' '){
        for(int i=0; i <= strlen(c); i++){
            c[i] = c[i+1];
        }
    }
    for(int i = 0; i <= strlen(c); i++){
        if (c[i] == ' ' && c[i+1] == ' '){
            for(int j = i+1; j <= strlen(c); j++){
                c[j] = c[j+1];
            }
            i--;
        } 
    }
    puts(c); 
    return 0;
}
```



