# IT4931_data_management_and_processing_lab_materials
Dữ liệu lớn yêu cầu cần có các cơ chế, kỹ thuật xử lý dữ liệu ở quy mô lớn và hiệu quả. Học phần này nhằm cung cấp cho người học các kiến thức về công nghệ lưu trữ dữ liệu lớn, các hệ quản trị cơ sở dữ liệu NoSQL, NewSQL, các nguyên lý xử lý dữ liệu song song, phân tán, theo khối, theo luồng, xử lý sự kiện phức tạp, quản lý luồng công việc. Bên cạnh đó, người học được làm quen và vận dụng các công nghệ xử lý dữ liệu lớn trên nền tảng Hadoop - Map Reduce, và Spark. Sau khi kết thúc học phần này người học có khả năng hiểu, lựa chọn, cài đặt, và vận hành các giải pháp lưu trữ và xử lý dữ liệu phù hợp dựa trên các kiến thức học được cho các bài toán ứng dụng cụ thể liên quan tới dữ liệu lớn.

# Copy the data
Original data url: https://github.com/databricks/Spark-The-Definitive-Guide/tree/master/data

Copy the original data to ./spark-lab/
## Start your cluster
docker-compose up -d

Your notebook key can be found by: docker logs pyspark-notebook 
## Clean your cluster
docker-compose down

