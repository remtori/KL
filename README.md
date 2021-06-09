# KL - Local demo

Lưu ý phải dùng Python 3.7 (hỗ trợ cả tensorflow 1 và 2)

## Data

- Tải thư mục data từ PRNet về, giải nén và đặt tên là data

- Tải thư mục KL về, giải nén và đặt tên là KL

## PRNet

### Khởi tạo môi trường / cài thư viện

```sh
python3 -m venv prn-env

source prn-env/bin/activate

pip install -r prnet.requirements.txt
```

### Chạy notebook

```sh
jupyter notebook PRNet.ipynb
```

## Model


### Khởi tạo môi trường / cài thư viện

```sh
python3 -m venv model-env

source model-env/bin/activate

pip install -r model.requirements.txt
```

### Chạy notebook

```sh
jupyter notebook Model.ipynb
```
