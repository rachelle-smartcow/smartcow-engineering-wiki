# 📼 TSConfig



```
{
    "compilerOptions": {
        "declaration": true,
        "declarationMap": true,
        "sourceMap": true,
        "target": "es5",
        "downlevelIteration": true,
        "lib": [
            "dom",
            "dom.iterable",
            "esnext"
        ],
        "skipLibCheck": true,
        "esModuleInterop": true,
        "allowSyntheticDefaultImports": true,
        "strict": true,
        "forceConsistentCasingInFileNames": true,
        "module": "es6",
        "moduleResolution": "node",
        "resolveJsonModule": true,
        "jsx": "react",
        "rootDir": ".",
        "baseUrl": "./src",
        "paths": {
            "$components/*": [
                "components/*"
            ],
            "$utils/*": [
                "utils/*"
            ],
            "$hooks/*": [
                "hooks/*"
            ]
        },
        "plugins": [
           
            {
                "name": "typescript-plugin-css-modules"
            }
        ],
        "typeRoots": [
            "./node_modules/@types",
            "./typings"
        ]
    },
    "exclude": [
        "node_modules"
    ]
}
```
