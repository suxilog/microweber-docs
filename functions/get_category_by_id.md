## get_category_by_id

get_category_by_id — returns category data as array or false

### Summary

    get_category_by_id($id);

### Return Values

`Array` with the category data or `false` if the category is found.

### Usage

    //get a category  
    $category_data = get_category_by_id(23);
    var_dump($category_data); 

    if($category_data != false){
    	print $category_data['title'];  
    	print $category_data['id'];
    	print $category_data['parent'];
    	print $category_data['position'];
    	print $category_data['created_at']; 
    	// and more... print_r($category_data);
    }

 