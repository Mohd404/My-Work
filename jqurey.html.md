```
<!DOCTYPE html>
<html>
<head>
    <title>Tree View</title>
    <script>
        src="C:\Users\Mr. X\Downloads/input1.json"
    </script>
    <style>
      #treeview, #treeview ul 
      {
        list-style-type: none;
      }
      #treeview li > ul 
      {
        display: none;
      }
      #treeview li:before 
      {
        content: "\2295";
        margin-right: 5px;
      }

      #treeview li.open:before 
      {
       content: "-";
      }
      #treeview li.close:before 
      {
        content: "\2296";
        margin-right: 5px;
      }

      #treeview li.close:before 
      {
       content: "-";
      }
    </style>

    <script>
      
    </script>
</head>
<body>
    <ul id="treeview">
        <li data-jstree='{"id": "course_id", "text": "course_name", "state": {"opened": true}}'>
          course_name
          <ul>
            <li data-jstree='{"id": "subject_id", "text": "subject_name", "state": {"opened": false}}'>
              subject_name
              <ul>
                <li data-jstree='{"id": "module_id", "text": "module_name", "state": {"opened": false}}'>
                  module_name
                  <ul>
                    <li data-jstree='{"id": "chapter_id", "text": "chapter_name", "state": {"opened": false}}'>
                      chapter_name
                      <ul>
                        <li data-jstree='{"id": "topic_id", "text": "topic_name"}'>
                          topic_name
                        </li>
                        <li data-jstree='{"id": "topic_id", "text": "topic_name"}'>
                          topic_name
                        </li>
                      </ul>
                    </li>
                    <li data-jstree='{"id": "chapter_id", "text": "chapter_name", "state": {"opened": false}}'>
                      chapter_name
                      <ul>
                        <li data-jstree='{"id": "topic_id", "text": "topic_name"}'>
                          topic_name
                        </li>
                        <li data-jstree='{"id": "topic_id", "text": "topic_name"}'>
                          topic_name
                        </li>
                      </ul>
                    </li>
                  </ul>
                </li>
              </ul>
            </li>
          </ul>
        </li>
      </ul>
      
    </body>
</html>
```
