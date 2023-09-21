# Search_context_from_wiki_with_faiss
Lib :  https://www.kaggle.com/datasets/jjinho/blingfire-018
blingfire để tách document thành dánh sách các câu đơn

push kaggle https://www.kaggle.com/datasets/tomokihirose/faiss-gpu-173-python310
Nguồn Facebook https://github.com/facebookresearch/faiss/tree/main
faiss tạo file.index  là dánh sách các document và phân cựm nội dung cần tìm để tìm điếm đô tương đồng đánh giá bằng score

setting 
!pip install -U /kaggle/input/faiss-gpu-173-python310/faiss_gpu-1.7.2-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl

Data wikipedia 2023-07-01
https://www.kaggle.com/datasets/jjinho/wikipedia-20230701
Bộ đa ta được lưu theo bảng chư cái 

https://www.kaggle.com/datasets/jjinho/wikipedia-2023-07-faiss-index
Bộ data wikipedia được mã hóa titel và câu đâu tiên trong nội dung bằng all-MiniLM-L6-v2 model from sentence_transformers to create the embedding.

Tìm kiếm nọi dung liên qua qua tiều đề và câu đầu tiên

