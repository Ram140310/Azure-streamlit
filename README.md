# demo-streamlit-azure
Demo repo to deploy Streamlit private repo to Azure service.


## Guideline

### Git Actions
- https://github.com/amrrs/streamlit_metric_dashboard/tree/main/.github/workflows

### Basic Section
1. Click App Serives and create app service
2. Select Resource Group
3. Write *app name*. 
4. Choose *code* (if you have container, choose container)
5. Choose runtime (programming language)
6. Select operating system (Linux is recommended)
7. Select region 
8. Select sku and size 

### Deployment 
1. Link your Github account
2. Set organization 
3. Select repo name 
4. Select branch 
5. Click create to deploy

### Configuration 
1. Setup startup command 
```cmd
python -m streamlit run main.py --server.port 8000 --server.address 0.0.0.0
```