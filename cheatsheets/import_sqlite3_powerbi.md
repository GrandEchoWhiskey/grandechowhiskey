db_path = r""

import sqlite3
import pandas as pd
conn = sqlite3.connect(db_path)
query_tables = "SELECT name FROM sqlite_master WHERE type='table'"
tables = pd.read_sql(query_tables, conn)
dataframes = {table: pd.read_sql(f"SELECT * FROM {table}", conn) for table in tables["name"]}
conn.close()
locals().update(dataframes)
