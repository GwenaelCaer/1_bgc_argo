# Develoment

```bash
# Create the build environment
mamba env create -n odatis-bgc-argo -f ci/requirements/environment.yml

# Update the environment with dev dependencies
mamba env update -n odatis-bgc-argo -f ci/requirements/environment-dev.yml

# Activate the environment
mamba activate odatis-bgc-argo

# # Build and install pytcube
# pip install -e . --no-deps
```