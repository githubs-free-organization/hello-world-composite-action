# Composite Action for React WebApp

This repo holds a Composite Action for building and deploying the build file to s3 bucket.
This can be called by the following way:
```
steps:
      - uses: actions/checkout@v4
      - id: foo
        uses: githubs-free-organization/hello-world-composite-action@main
                with:
                  aws-access-key-id: ${{ secrets.AWS_ACCESS_ID }}
                  aws-secret-access-key: ${{ secrets.AWS_SECRET_KEY }}
```
