***
# My CV #
***
### Name and surname
* Soroko Denis
### Contacts for communication
* phone number: +375(29) 6974675;
* telegram name: it_dnk
### Information about me
* I am 30. I work as an engineer, I want to study the skills of a WEB developer, and in the future to engage in this activity. We advised to start with Rolling Scopes School. I learned about Rolling Scopes School from friends, I liked the presentation of the material, the emphasis on practice and motivation, I decided to go towards my goal with your help. I'm sure everything will work out!
### Skills
* HTML;
* CSS; 
* SASS; 
* PHP; 
* GIT
### Code examples
```
<?php
foreach ($_POST as $post=>$value ) {
$$post = $value;
}
$db = mysqli_connect('localhost', 'root', 'root', 'db_wayup' );
if (!$db) {
    die('Error connect DB');
}
$query_write = mysqli_query($db, "INSERT INTO products (id, name, description, category_id, price) VALUES (NULL, '$name', '$description', '$category_id', '$price')");
if (!$query_write) {
echo 'Ошибка записи в БД';
} else {
echo 'Данные записаны в БД' . '<br><br>';
$tableData = '<tr>
                        <td>ИМЯ</td>
                        <td>ОПИСАНИЕ</td>
                        <td>КАТЕГОРИЯ</td>
                        <td>ЦЕНА</td>
                      </tr>';
        $query_selects = mysqli_query($db, "SELECT * FROM products");
        while ($product = mysqli_fetch_assoc($query_selects)) {
            $tableData .= '<tr><td>' . $product['name'] . '</td>' .
                '<td>' . $product['description'] . '</td>' .
                '<td>' . $product['category_id'] . '</td>' .
                '<td>' . $product['price'];
        }

    echo '<table border="1">' . $tableData . '</table>';
}
```
### Experience
* No work experience at the moment
### Education
* higher education, engineer, management specialist
* took PHP courses from Brain Force
### English language
* Beginner (A1)
