# Markdown
### Header
This is a normal paragraph:

	#This is a H1
end code block.

## 블록인용문자

	>this is a blockqute.
>this is blockqute.
> this is blockqute.
>>this is blockqute.

## 목록
* 순서있는 목록

	1. first
 		2. second
 		3. third

1. first
2. second
3. third

* 순서없는 목록
 		* first
			* second
				* third

		+ first
		+ second
		+ third

* first
	* second
		* third

* first
* second
* third	

## 코드
	코드 사용법
	이렇게 code나 민무뉘 바탕에 글을 적고 싶으면
	tab키를 이용해서 들여쓰기를 하게 되면 적용이 된다
	ex)this is Test code:

		markdown!!
	end line

	ex)
	this is Test code:
	```
	int main(){
		print("hello world");
	}
	```
ex)this is Test code:

	markdown!!
end 

ex)
this is Test code:
```
int main(){
	print("hello world");
}
```

## 링크

* 참조링크

 		[link keyword][id]
		[id]: URL

		ex)[Chromium] https://www.chromium.org/

[Chromium] https://www.chromium.org/

* 인라인 링크

		[Title](link)
 		ex)[Chromium](https://www.chromium.org/)

[Chromium](https://www.chromium.org/)

## 강조

	**Strong Word**
	~~Remove Word~~

**Strong Word**
~~Remove Word~~

## 이미지

	![Alt text](/path/to/img.jpg)
	![Alt text](/path/to/img.jpg "optional title")
	
![Alt text](./chromium.png)

## 동영상
```
@[동영상](https://www.youtube.com/watch?v=CS2bLJMrI6Y)
```
@[아이유 인기곡](https://www.youtube.com/watch?v=CS2bLJMrI6Y)

### 참고

* [markdown사용법] https://gist.github.com/ihoneymon/652be052a0727ad59601
