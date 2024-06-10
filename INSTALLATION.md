# installation

1. using docker: docker compose -f docker/docker-compose.yaml build mmdetection3d
2. using conda/mamba:
    - conda env create -f environment.yaml
    - mamba env create -f environment.yaml
3. activate conda env: mamba activate mmdetection3d
4. pip install openmim && mim install mmengine mmcv mmdet
5. pip install --no-cache-dir -e .
