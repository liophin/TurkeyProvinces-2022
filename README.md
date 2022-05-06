# Turkey-Provinces
All provinces and districts in Turkey (2022)

# Design

```sql
CREATE TABLE [Province] (
	[id] [int] IDENTITY(1,1) NOT NULL,
	[Title] [nvarchar](50) NULL
)
  
CREATE TABLE [District] (
	[id] [int] IDENTITY(1,1) NOT NULL,
	[ProvinceID] [int] NULL,
	[Title] [nvarchar](50) NULL
)
```
