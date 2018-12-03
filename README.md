# docker
1. 生成requirements:

	```
	pip install pipreqs
	pipreqs ./
	
	```
	
2. 在 api_assesment_vocabulary 目录下运行：

   ```
   docker build -t api_assesment_vocabulary .
   ```

   建立 image


3. 运行

   ```
   docker run -p 8080:8080 api_assesment_vocabulary
   ```

   启动微服务


4. 单元测试 unit_test.py 在 api_assesment_vocabulary\app\test 目录下，运行

   ```
   python unit_test.py
   ```

   进行单元测试

