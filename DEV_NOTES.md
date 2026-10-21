使用原版的requirements.txt会有依赖冲突，推荐使用 uv sync 还原环境

同时使用uv时要安装pip(uv pip install pip)避免Cerebrum 加载 agent 时硬编码调用 python -m pip