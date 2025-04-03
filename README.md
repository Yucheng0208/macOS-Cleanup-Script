# mac-cleanup-scripts

A simple and safe macOS cache and log cleaner script.  
Keep your Mac clean and efficient with one command.

## 🚀 Features
- Clean system cache
- Remove application logs
- Clear Xcode DerivedData (if exists)
- Clean browser caches (Chrome, Brave, Edge, and Safari)
- Empty the trash bin
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
> This script will delete the cache and temporary files only.
> No application or system files will be affected.
> However, some apps may rebuild the cache when reopened, slowing down the first launch.

# License
This open-source project is licensed under the [MIT License](LICENSE).
