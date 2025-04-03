# mac-cleanup-scripts

A simple and safe macOS cache and log cleaner script.  
Keep your Mac clean and efficient with one command.

## 🚀 Features
- Clean system cache
- Remove application logs
- Clear Xcode DerivedData (if exists)
- Clean browser caches (Chrome, Brave, Edge, Safari)
- Empty trash bin
- Clear QuickLook thumbnail cache

## 📄 Usage
1. Clone the repository:
```bash
git clone https://github.com/your-username/mac-cleanup-scripts.git
cd mac-cleanup-scripts
```

2. Give execution permission:
```bash
chmod +x clean_cache.sh
```

3. Run the script:
```bash
./clean_cache.sh
```

> [!WARNING]
> This script will delete cache and temporary files only.
> No application or system files will be affected.
> However, some apps may rebuild cache when reopened, which might slow down the first launch.
