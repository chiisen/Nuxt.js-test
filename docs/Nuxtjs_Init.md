# npx
如果您安裝的 npm 為 5.2.0 以上，npx 會自動安裝在您的電腦裡面。  
npx 的安裝的方式為：  
```
npx create-nuxt-app <project-name>
```
使用 launch.json 執行報錯
```
i Using default Tailwind CSS file from runtime/tailwind.css             nuxt:tailwindcss 15:09:25

 FATAL  nuxt.options._layers is not iterable 
```
在執行下面指令即可解決
```
npm install --save-dev @nuxtjs/tailwindcss@^6
```
