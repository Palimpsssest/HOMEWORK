# Postman. HW_1


__Создать запросы в Postman:__

`Protocol: http`

`IP: 162.55.220.72`

`Port: 5005`

## EP_1

|Method | EndPoint | request url params |
|-------|----------|--------------------|
|GET    |get_method|name: str; age: int |


__response:__
```
[
    “Str”,
    “Str”   
]
```
***

## EP_2

|Method | EndPoint  |      request form data          |
|-------|-----------|---------------------------------|
|POST   |user_info_3|name: str; age: int ; salary: int|



__response:__ 
```
{'name': name,
          'age': age,
          'salary': salary,
          'family': {'children': [['Alex', 24], ['Kate', 12]],
                     'u_salary_1_5_year': salary * 4}}
```

***

## EP_3

|Method | EndPoint    |      request url params        |
|-------|-------------|--------------------------------|
|GET    |object_info_1|name: str; age: int; weight: int|


__response:__
```
{'name': name,
          'age': age,
          'daily_food': weight * 0.012,
          'daily_sleep': weight * 2.5}
```


***

## EP_4

|Method | EndPoint    |      request url params        |
|-------|-------------|--------------------------------|
|GET    |object_info_2|name: str; age: int; salary: int|


__response:__
```
{'start_qa_salary': salary,
          'qa_salary_after_6_months': salary * 2,
          'qa_salary_after_12_months': salary * 2.7,
          'qa_salary_after_1.5_year': salary * 3.3,
          'qa_salary_after_3.5_years': salary * 3.8,
          'person': {'u_name': [user_name, salary, age],
                     'u_age': age,
                     'u_salary_5_years': salary * 4.2}
          }
```


***

## EP_5

|Method | EndPoint    |      request url params        |
|-------|-------------|--------------------------------|
|GET    |object_info_3|name: str; age: int; salary: int|

__response:__
```
{'name': name,
          'age': age,
          'salary': salary,
          'family': {'children': [['Alex', 24], ['Kate', 12]],
                     'pets': {'cat':{'name':'Sunny',
                                     'age': 3},
                              'dog':{'name':'Luky',
                                     'age': 4}},
                     'u_salary_1_5_year': salary * 4}
          }
 ```


****

## EP_6
|Method | EndPoint    |      request url params        |
|-------|-------------|--------------------------------|
|GET    |object_info_4|name: str; age: int; salary: int|


__response:__
```
{'name': name,
          'age': int(age),
          'salary': [salary, str(salary * 2), str(salary * 3)]}
```


## EP_7

|Method | EndPoint  |      request form data          |
|-------|-----------|---------------------------------|
|POST   |user_info_2|name: str; age: int ; salary: int|

__response:__
```
{'start_qa_salary': salary,
          'qa_salary_after_6_months': salary * 2,
          'qa_salary_after_12_months': salary * 2.7,
          'qa_salary_after_1.5_year': salary * 3.3,
          'qa_salary_after_3.5_years': salary * 3.8,
          'person': {'u_name': [user_name, salary, age],
                     'u_age': age,
                     'u_salary_5_years': salary * 4.2}
          }
 ```
 ***