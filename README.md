# Python Modules for Real-World Projects

<p>Welcome to this curated documentation of essential Python modules widely used in industry-level projects. This repository aims to provide clear, concise, and practical explanations of Python&rsquo;s most powerful standard and third-party libraries. Whether you're a beginner exploring real-world applications or a professional brushing up on tools used in production environments, this collection will serve as a handy reference and learning resource.</p>

## 1. os - Operating System Interface

<ul>
<li>Provides a portable way of using operating system&ndash;dependent functionality.</li>
<li>It plays a critical role in building scripts and applications that need to interact with the underlying file system, manage environment variables, or execute system commands.</li>
</ul>

```python
import os
```

<p><strong>To list all the attributes, functions, classes, variables, etc. defined in the <code data-start="207" data-end="211">os</code> module.</strong></p>

```python
print(dir(os))
```

![image](https://github.com/user-attachments/assets/27d9a52e-5f3a-4850-88ac-c83a4dcb624b)


### File and Directory Operations

<p><strong>a) Get current working directory</strong></p>

```python
print(os.getcwd())
```

![image](https://github.com/user-attachments/assets/202fac38-399a-44b1-b61b-36cad2da4304)

<p><strong>b) Change current working directory</strong></p>

```python
os.chdir('/path/to/directory')
os.chdir('C:\\Users\\OmarA\\OneDrive\\Documents')
print(os.getcwd())
```


![image](https://github.com/user-attachments/assets/2a663dbf-7aa4-4d12-9d38-657f570af32d)

<p><strong>c) List directory contents</strong></p>

```python
print(os.listdir())
```

![image](https://github.com/user-attachments/assets/3264ca61-2558-419e-9a1e-b9e224940df0)

<p><strong>d)</strong> <strong data-start="668" data-end="694">Create a new directory</strong></p>

```python
os.mkdir('new_directory')

os.mkdir('C:\\Users\\OmarA\\OneDrive\\Documents\\Data Engineer\\Azure Data Engineer\\Loading Files to ADLSg2\\new_dir')
print(os.listdir())
```

![image](https://github.com/user-attachments/assets/805872a6-922b-4f39-a26d-855adb7075a5)


<p><strong data-start="743" data-end="778">e) Create intermediate directories</strong></p>

```python
os.makedirs('dir1/dir2/dir3')

```

<p><strong data-start="743" data-end="778">f) Remove a file</strong></p>

```python
os.remove('file_name')
```

<p><strong data-start="743" data-end="778">g)&nbsp; Remove a directory</strong></p>

```python
os.rmdir('empty_directory')
```

<p><strong data-start="743" data-end="778">h) Remove directories recursively</strong></p>

```python
os.removedirs('dir1/dir2/dir3')
```

<p><strong>i) Rename a file or directory</strong></p>

```python
os.rename('old_name.txt', 'new_name.txt')
```
