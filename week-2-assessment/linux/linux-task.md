## Exercise on Linux

### 1. Users and Group Permissions

- A user is the owner of the file. By default, the person who created a file becomes its owner. Hence, a user is also sometimes called an owner.
- Group: A user- group can contain multiple users. All users belonging to a group will have the same Linux group permissions access to the file.
- Other: Any other user who has access to a file. This person has neither created the file, nor he belongs to a usergroup who could own the file.

#### Three Permissions in Linux

- Read: This permission give you the authority to open and read a file. Read permission on a directory gives you the ability to lists its content.
- Write: The write permission gives you the authority to modify the contents of a file. The write permission on a directory gives you the authority to add, remove and rename files stored in the directory.
- Execute: In Windows, an executable program usually has an extension “.exe” and which you can easily run. In Unix/Linux, you cannot run a program unless the execute permission is set.

![permission](./img/Permis_system.png)
<br>
![permission](./img/its_a_file.png)
<br>
![permission](./img/no_execute.png)
<br>
![permission](<./img/permission(1).png>)

Absolute(Numeric) Mode

| Number | Permission Type       | Symbol |
| ------ | --------------------- | ------ |
| 0      | No Permission         | -      |
| 1      | Execute               | -X     |
| 2      | Write                 | -W-    |
| 3      | Execute + Write       | -WX    |
| 4      | Read                  | r-     |
| 5      | Read + Execute        | r-x    |
| 6      | Read +Write           | rw-    |
| 7      | Read + Write +Execute | rwx    |

|

### 2. Create (3) groups and (15) users

#### Create (3) Groups

![groups](./img/addgroup.png)

- List all groups
  ![groups](./img/listgoups.png)

#### Create (15) Users

![groups](./img/useradd.png)

- List all users
  ![groups](./img/listusers.png)

### 3. Assign the 15 users across the 3 groups

- List all users belonging to "deploy group"
  ![groups](./img/deploy.png)
- List all users belonging to "managers group"
  ![groups](./img/managers.png)
- List all users belonging to "deploy group"
  ![groups](./img/maintainers.png)
  <br>
- List of groups
  ![groups](./img/groups.png)

### 4. Demonstrate that user(s) in a group cannot access files/folders that belong to another group unless they are added to that group.

- I switch to user "calvin"
  ![calvin](./img/calvin.png)
- I create a file
  ![new file](./img/touchfile.png)
- I change the newly created file permission
  ![new file](./img/changeper.png)
- Using "test user" from a different group
  ![new file](./img/perde.png)
  - Add "test user" to deploy group access the file
    ![new file](./img/addme.png)
