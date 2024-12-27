# Subsets Integration Template

Template action for Subsets data integrations using python 3.11 and poetry.

## Usage

```yaml
jobs:
  integration:
    uses: subsets-dev/integration-template@v1
    with:
      run_command: ./run.sh
    secrets:
      SUBSETS_API_KEY: ${{ secrets.SUBSETS_API_KEY }}
```

