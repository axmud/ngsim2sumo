
# copy the command line codes below and run it

```cnd
set PROJECT=NGSIM
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/0.10.8/install.ps1 | iex"
git clone https://github.com/axmud/ngsim2sumo.git %PROJECT%
cd %PROJECT%
uv sync
.venv\Scripts\activate
jupyter notebook
```

[Youtube Video Link](https://youtu.be/VlsaDN1QHMw)
