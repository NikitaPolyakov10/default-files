# prettier config

.prettierrc

{
    "printWidth": 80,
    "tabWidth": 2,
    "useTabs": false,
    "semi": true,
    "singleQuote": true,
    "quoteProps": "as-needed",
    "trailingComma": "es5",
    "bracketSpacing": true,
    "arrowParens": "avoid",
    "endOfLine": "lf",
    "overrides": [
        {
            "files": ["*.css", "*.scss", "*.less"],
            "options": {
                "singleQuote": false
            }
        }
    ]
}
