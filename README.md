# knowledge_graph
# Before running the code, establish a connection to the Neo4j database.

# 1. Load relationships from the Excel file
### 1. The Excel file is stored in the 'graph_data' folder, and you can add or remove files as needed.
### 2. Run the 'Create_KG.py' script.
You can replace 'file1 = r'graph_data\relation.xlsx'' with the name of your relationship file, and add the corresponding entities in 'file2 = r'graph_data\entity.xlsx'' to meet your specific requirements.

# 2. Process for adding properties to nodes
### 1. Ensure that the node has already been created before adding properties.
### 2. Add the property triples to the 'graph_data\attribute.xlsx' file.
You can replace 'excel_file = r'graph_data\attribute.xlsx'' with the name of your attribute file as needed.
### 3. Run the 'Add_attribute.py' script.
