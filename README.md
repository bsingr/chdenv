# chdenv

Change .env files via symlink

    ls .env*
    # .env -> .env.integration
    # .env.approval
    # .env.develop.example
    # .env.integration

    chdenv a*
    # Using .env.approval

    ls .env*
    # .env -> .env.approval
    # .env.approval
    # .env.develop.example
    # .env.integration
