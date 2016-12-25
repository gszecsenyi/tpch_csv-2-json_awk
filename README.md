### tpch 2 json convert awk files

# Execution
awk -f lineitem.awk lineitem.csv > lineitem.json
awk -f orders.awk orders.csv > orders.json
