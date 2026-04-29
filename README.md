
# copy the command line codes below and run it

```cnd
set PROJECT=NGSIM
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/0.10.8/install.ps1 | iex"
git clone https://github.com/axmud/ngsim2sumo.git %PROJECT%
uv init %PROJECT% -p "==3.10.20"
cd %PROJECT%
uv add notebook==7.5.5
uv add tqdm==4.67.3
uv add pandas==2.3.3
uv add pyproj==3.7.1
uv add ipywidgets==8.1.8
jupyter notebook
```
